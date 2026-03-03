<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eurojackpot Live Smart Gen</title>
    <style>
        :root { --bg: #0d1117; --card: #161b22; --accent: #58a6ff; --text: #c9d1d9; }
        body { font-family: 'Segoe UI', sans-serif; background: var(--bg); color: var(--text); display: flex; justify-content: center; padding: 20px; margin: 0; }
        .container { background: var(--card); padding: 25px; border-radius: 20px; box-shadow: 0 10px 40px rgba(0,0,0,0.6); max-width: 500px; width: 100%; text-align: center; border: 1px solid #30363d; }
        
        #timer { font-size: 1.1rem; margin-bottom: 20px; color: #ffa657; font-weight: bold; }
        .last-draw-info { font-size: 0.8rem; background: #0d1117; padding: 10px; border-radius: 10px; margin-bottom: 20px; border: 1px dashed #30363d; }
        
        .numbers-display { display: flex; justify-content: center; gap: 8px; margin: 20px 0; min-height: 60px; }
        .ball { width: 45px; height: 45px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: bold; font-size: 1.1rem; color: #000; transition: transform 0.3s; }
        .main-ball { background: radial-gradient(circle at 30% 30%, #f2cc60, #d4a017); }
        .euro-ball { background: radial-gradient(circle at 30% 30%, #f85149, #b91d1d); color: white; }
        
        button { background: #238636; color: white; border: none; padding: 16px; font-size: 1.1rem; border-radius: 12px; cursor: pointer; width: 100%; font-weight: bold; margin-top: 10px; }
        button:disabled { background: #161b22; color: #484f58; cursor: not-allowed; border: 1px solid #30363d; }
        
        .filters-status { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; font-size: 0.75rem; margin-top: 20px; text-align: left; opacity: 0.8; }
        .sum-box { font-weight: bold; color: var(--accent); margin: 10px 0; }
    </style>
</head>
<body>

<div class="container">
    <h2 style="margin-top:0; color:var(--accent)">Eurojackpot AI</h2>
    <div id="timer">Ładowanie danych...</div>

    <div class="last-draw-info" id="last-results">
        Pobieranie ostatnich wyników z sieci...
    </div>

    <div class="sum-box" id="sum-val">Suma: --</div>
    <div class="numbers-display" id="result"></div>

    <button id="gen-btn" onclick="generate()" disabled>CZEKAJ NA DANE...</button>

    <div class="filters-status">
        <div>✅ Suma: 110 - 130</div>
        <div>✅ Sektory: Smart Weight</div>
        <div>✅ Parzystość: 2:3 / 3:2</div>
        <div>✅ Wykluczenie: Ostatnie 3</div>
    </div>
</div>

<script>
    let excludedNumbers = [];

    // 1. POBIERANIE DANYCH LIVE
    async function fetchResults() {
        try {
            // Korzystamy z otwartego API lottoland/magayo dla wyników
            const response = await fetch('https://www.lottoland.com/api/drawings/euroJackpot');
            const data = await response.json();
            
            // Pobieramy 3 ostatnie losowania
            const draws = data.lastItems || [];
            excludedNumbers = [];
            
            draws.slice(0, 3).forEach(draw => {
                excludedNumbers.push(...draw.numbers);
            });

            document.getElementById('last-results').innerHTML = `
                <b>Ostatnie wykluczone liczby:</b><br>
                <small>${[...new Set(excludedNumbers)].sort((a,b)=>a-b).join(', ')}</small>
            `;
            document.getElementById('gen-btn').disabled = false;
            document.getElementById('gen-btn').innerText = "GENERUJ SMART LICZBY";
        } catch (e) {
            document.getElementById('last-results').innerHTML = "Błąd pobierania danych. Używam filtrów statycznych.";
            excludedNumbers = [1, 5, 12, 20, 33]; // Fallback
            document.getElementById('gen-btn').disabled = false;
        }
    }

    // 2. LOGIKA GENERATORA
    function getWeight(n) {
        if (excludedNumbers.includes(n)) return 0; // Twarde wykluczenie
        if ((n >= 11 && n <= 20) || (n >= 31 && n <= 40)) return 6; // Sektory PRIO
        if (n >= 21 && n <= 30) return 1; // Sektor LOW
        return 3;
    }

    function generate() {
        let finalMain = [];
        let finalSum = 0;
        
        for (let attempt = 0; attempt < 10000; attempt++) {
            let temp = [];
            let pool = [];
            for (let i = 1; i <= 50; i++) {
                for (let j = 0; j < getWeight(i); j++) pool.push(i);
            }

            while (temp.length < 5) {
                let n = pool[Math.floor(Math.random() * pool.length)];
                if (!temp.includes(n)) temp.push(n);
            }

            let sum = temp.reduce((a, b) => a + b, 0);
            let evens = temp.filter(x => x % 2 === 0).length;
            
            // FILTRY
            if (sum < 110 || sum > 130) continue; // Suma ze zdjęcia
            if (evens < 2 || evens > 3) continue; // Parzystość
            
            temp.sort((a, b) => a - b);
            let gapOk = true;
            for(let i=0; i<4; i++) if(temp[i+1] - temp[i] < 3) gapOk = false;
            
            if (gapOk) {
                finalMain = temp;
                finalSum = sum;
                break;
            }
        }

        let euro = [];
        while(euro.length < 2) {
            let n = Math.floor(Math.random() * 12) + 1;
            if(!euro.includes(n)) euro.push(n);
        }

        display(finalMain, euro.sort((a,b)=>a-b), finalSum);
    }

    function display(main, euro, sum) {
        const res = document.getElementById('result');
        document.getElementById('sum-val').innerText = `Suma: ${sum}`;
        res.innerHTML = '';
        main.forEach(n => res.innerHTML += `<div class="ball main-ball">${n}</div>`);
        euro.forEach(n => res.innerHTML += `<div class="ball euro-ball">${n}</div>`);
    }

    // 3. TIMER
    function updateTimer() {
        const now = new Date();
        const next = new Date();
        let drawDays = [2, 5]; // Wtorek, Piątek
        let targetDay = drawDays.find(d => d > now.getDay() || (d === now.getDay() && now.getHours() < 20)) || 2;
        let diff = (targetDay - now.getDay() + 7) % 7;
        if (diff === 0 && now.getHours() >= 20) diff = (targetDay === 2 ? 3 : 4);
        next.setDate(now.getDate() + diff);
        next.setHours(20, 0, 0, 0);
        
        const ms = next - now;
        const d = Math.floor(ms / 86400000);
        const h = Math.floor((ms % 86400000) / 3600000);
        const m = Math.floor((ms % 3600000) / 60000);
        const s = Math.floor((ms % 60000) / 1000);
        document.getElementById('timer').innerText = `Następne losowanie: ${d}d ${h}h ${m}m ${s}s`;
    }

    setInterval(updateTimer, 1000);
    fetchResults();
</script>

</body>
</html>
