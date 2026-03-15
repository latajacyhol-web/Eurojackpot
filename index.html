<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>⚡ EuroJackpot</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:#0a0e1a;color:#e0e8ff;font-family:sans-serif;min-height:100vh;padding:14px 10px 50px;background-image:radial-gradient(ellipse at 20% 10%,rgba(245,200,66,0.07) 0%,transparent 60%)}
.wrap{max-width:440px;margin:0 auto;display:flex;flex-direction:column;gap:12px}
.title{text-align:center;font-family:'Orbitron',monospace;font-size:1.5rem;font-weight:900;letter-spacing:3px;background:linear-gradient(135deg,#f5c842,#e8a020);-webkit-background-clip:text;-webkit-text-fill-color:transparent;padding:8px 0}
.box{background:#111827;border:1px solid #1e2d45;border-radius:12px;padding:12px 14px}
.lbl{font-size:0.6rem;color:#5a7080;text-transform:uppercase;letter-spacing:2px;margin-bottom:8px}
.langs{display:flex;gap:6px;flex-wrap:wrap}
.lang-btn{background:rgba(255,255,255,0.03);border:1px solid #1e2d45;border-radius:7px;padding:5px 9px;font-size:0.75rem;font-weight:700;color:#6a7f90;cursor:pointer}
.lang-btn.active{background:rgba(245,200,66,0.2);border-color:#f5c842;color:#f5c842}
.countdown{background:linear-gradient(135deg,#1a1200,#2a1e00);border:1px solid #e8a020;border-radius:12px;padding:14px;text-align:center}
.cd-lbl{font-size:0.6rem;color:#e8a020;text-transform:uppercase;letter-spacing:2px}
.cd-val{font-family:'Orbitron',monospace;font-size:1.3rem;font-weight:700;color:#f5c842;margin-top:4px}
.stats{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.stat{background:#111827;border:1px solid #1e2d45;border-radius:10px;padding:12px;text-align:center}
.stat-lbl{font-size:0.6rem;color:#5a7080;text-transform:uppercase}
.stat-val{font-size:1rem;font-weight:700;margin-top:3px;font-family:'Orbitron',monospace}
.result-box{background:#111827;border:1px solid #1e2d45;border-radius:14px;padding:18px;min-height:110px;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px}
.balls{display:flex;gap:7px;flex-wrap:wrap;justify-content:center}
.ball{border-radius:50%;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-weight:700;font-family:'Orbitron',monospace}
.ball-gold{background:radial-gradient(circle at 35% 35%,#fff8dc,#e8a020);color:#1a0a00;box-shadow:0 3px 12px rgba(245,200,66,0.4)}
.ball-blue{background:radial-gradient(circle at 35% 35%,#a0d4ff,#1565c0);color:#fff;box-shadow:0 3px 12px rgba(21,101,192,0.4)}
.sep{width:1px;background:#1e2d45;margin:0 3px;align-self:stretch}
.gen-btn{background:linear-gradient(135deg,#27ae60,#1e8449);border:none;border-radius:12px;padding:16px;width:100%;font-size:1rem;font-weight:700;letter-spacing:2px;color:#fff;cursor:pointer;font-family:'Orbitron',monospace}
.filters{display:grid;grid-template-columns:1fr 1fr;gap:7px}
.fil-btn{border-radius:8px;padding:8px 10px;font-size:0.75rem;font-weight:600;cursor:pointer;display:flex;align-items:center;gap:5px;text-align:left;border:1px solid}
.fil-on{background:rgba(39,174,96,0.15);border-color:#27ae60;color:#7dffb0}
.fil-off{background:rgba(230,150,0,0.1);border-color:#e8a020;color:#ffd77a}
.draw{margin-bottom:10px;padding-bottom:10px;border-bottom:1px solid #1e2d45}
.draw:last-child{margin-bottom:0;padding-bottom:0;border-bottom:none}
.draw-header{display:flex;justify-content:space-between;margin-bottom:6px}
.draw-date{font-size:0.65rem;color:#e8a020;font-weight:700}
.draw-jp{font-size:0.65rem;color:#f5c842;font-weight:700}
.hist-row{display:flex;align-items:center;gap:5px;flex-wrap:wrap;margin-bottom:6px}
.hist-row:last-child{margin-bottom:0}
.hist-sum{margin-left:auto;font-size:0.65rem;color:#5a7080}
.press-txt{font-size:0.85rem;color:#5a7080}
.res-info{font-size:0.65rem;color:#5a7080}
.hist-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
.clr-btn{background:none;border:none;color:#5a7080;cursor:pointer;font-size:0.75rem}
.fil-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}
.info-btn{background:rgba(79,195,247,0.15);border:1px solid #4fc3f7;border-radius:7px;padding:4px 10px;font-size:0.7rem;font-weight:700;color:#4fc3f7;cursor:pointer}
.modal-overlay{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.85);z-index:1000;overflow-y:auto;padding:20px 12px}
.modal-overlay.open{display:flex;align-items:flex-start;justify-content:center}
.modal{background:#111827;border:1px solid #1e2d45;border-radius:16px;padding:20px;width:100%;max-width:440px;margin:auto}
.modal-title{font-family:'Orbitron',monospace;font-size:1rem;font-weight:900;color:#f5c842;margin-bottom:16px;text-align:center}
.modal-item{background:#0d1520;border:1px solid #1e2d45;border-radius:10px;padding:12px 14px;margin-bottom:10px}
.modal-item:last-child{margin-bottom:0}
.modal-item-name{font-size:0.8rem;font-weight:700;color:#7dffb0;margin-bottom:5px}
.modal-item-desc{font-size:0.75rem;color:#8a9ab0;line-height:1.5}
.modal-close{background:linear-gradient(135deg,#27ae60,#1e8449);border:none;border-radius:10px;padding:12px;width:100%;font-size:0.9rem;font-weight:700;color:#fff;cursor:pointer;margin-top:16px}
</style>
</head>
<body>
<div class="wrap">
  <div class="title">⚡ EUROJACKPOT</div>
  <div class="box">
    <div class="lbl">🌐 Language / Język</div>
    <div class="langs" id="langs"></div>
  </div>
  <div class="countdown">
    <div class="cd-lbl" id="cd-lbl">🕐 Następne losowanie</div>
    <div class="cd-val" id="countdown">--</div>
    <div style="margin-top:8px;font-size:0.65rem;color:#e8a020;letter-spacing:1px;text-transform:uppercase">🏆 <span id="jackpot-lbl">Jackpot</span></div>
    <div style="font-family:'Orbitron',monospace;font-size:1.4rem;font-weight:900;color:#f5c842;margin-top:2px" id="jackpot-val">€22,000,000</div>
  </div>
  <div class="stats">
    <div class="stat"><div class="stat-lbl">Suma</div><div class="stat-val" id="s-sum" style="color:#5a7080">--</div></div>
    <div class="stat"><div class="stat-lbl">Szansa</div><div class="stat-val" style="color:#f5c842">1:140M</div></div>
    <div class="stat"><div class="stat-lbl">Próby</div><div class="stat-val" id="s-tries" style="color:#4fc3f7">0</div></div>
    <div class="stat"><div class="stat-lbl" id="s-fil-lbl">Filtry</div><div class="stat-val" id="s-fil" style="color:#4fc3f7">6/7</div></div>
  </div>
  <div class="result-box" id="result-box">
    <div class="press-txt" id="press-txt">Naciśnij przycisk aby wygenerować</div>
  </div>
  <button class="gen-btn" id="gen-btn">🧠 GENERUJ SMART</button>
  <div class="box">
    <div class="fil-header">
      <div class="lbl" id="fil-lbl">Filtry inteligentne</div>
      <button class="info-btn" onclick="openModal()">ℹ️ Info</button>
    </div>
    <div class="filters" id="filters"></div>
  </div>
  <div class="modal-overlay" id="modal-overlay" onclick="closeModalOutside(event)">
    <div class="modal">
      <div class="modal-title" id="modal-title">📋 FILTRY INFO</div>
      <div id="modal-content"></div>
      <button class="modal-close" id="modal-close" onclick="closeModal()">✕ Zamknij</button>
    </div>
  </div>
  <div class="box">
    <div class="lbl" id="ld-lbl">📊 Ostatnie losowania</div>
    <div id="draws"><div style="text-align:center;color:#5a7080;font-size:0.8rem;padding:12px">⏳ Pobieranie...</div></div>
  </div>
  <div class="box" id="hist-box" style="display:none">
    <div class="hist-header">
      <div class="lbl" id="hist-lbl">🕓 Historia</div>
      <button class="clr-btn" id="clr-btn">✕ wyczyść</button>
    </div>
    <div id="history"></div>
  </div>
</div>
<script>
const LANGS={pl:{flag:"🇵🇱",n:"PL"},en:{flag:"🇬🇧",n:"EN"},nl:{flag:"🇳🇱",n:"NL"},de:{flag:"🇩🇪",n:"DE"},es:{flag:"🇪🇸",n:"ES"},it:{flag:"🇮🇹",n:"IT"},fr:{flag:"🇫🇷",n:"FR"},fi:{flag:"🇫🇮",n:"FI"},et:{flag:"🇪🇪",n:"ET"},hr:{flag:"🇭🇷",n:"HR"},is:{flag:"🇮🇸",n:"IS"},no:{flag:"🇳🇴",n:"NO"},sv:{flag:"🇸🇪",n:"SV"},lv:{flag:"🇱🇻",n:"LV"},lt:{flag:"🇱🇹",n:"LT"},cs:{flag:"🇨🇿",n:"CS"},hu:{flag:"🇭🇺",n:"HU"},sk:{flag:"🇸🇰",n:"SK"},sl:{flag:"🇸🇮",n:"SL"},el:{flag:"🇬🇷",n:"EL"}};
const T={pl:{g:"🧠 GENERUJ SMART",nd:"🕐 Następne losowanie",ld:"📊 Ostatnie losowania",fil:"Filtry inteligentne",hi:"🕓 Historia",pr:"Naciśnij przycisk aby wygenerować",clr:"✕ wyczyść",sf:"Filtry",jp:"Jackpot następnego losowania"},en:{g:"🧠 GENERATE SMART",nd:"🕐 Next draw",ld:"📊 Last draws",fil:"Smart filters",hi:"🕓 History",pr:"Press button to generate",clr:"✕ clear",sf:"Filters",jp:"Next draw jackpot"},nl:{g:"🧠 GENEREER SLIM",nd:"🕐 Volgende trekking",ld:"📊 Laatste trekkingen",fil:"Slimme filters",hi:"🕓 Geschiedenis",pr:"Druk op knop",clr:"✕ wissen",sf:"Filters",jp:"Volgende jackpot"},de:{g:"🧠 SMART GENERIEREN",nd:"🕐 Nächste Ziehung",ld:"📊 Letzte Ziehungen",fil:"Intelligente Filter",hi:"🕓 Verlauf",pr:"Schaltfläche drücken",clr:"✕ löschen",sf:"Filter",jp:"Nächster Jackpot"},es:{g:"🧠 GENERAR SMART",nd:"🕐 Próximo sorteo",ld:"📊 Últimos sorteos",fil:"Filtros inteligentes",hi:"🕓 Historial",pr:"Presiona el botón",clr:"✕ borrar",sf:"Filtros",jp:"Próximo jackpot"},it:{g:"🧠 GENERA SMART",nd:"🕐 Prossima estrazione",ld:"📊 Ultime estrazioni",fil:"Filtri intelligenti",hi:"🕓 Cronologia",pr:"Premi il pulsante",clr:"✕ cancella",sf:"Filtri",jp:"Prossimo jackpot"},fr:{g:"🧠 GÉNÉRER SMART",nd:"🕐 Prochain tirage",ld:"📊 Derniers tirages",fil:"Filtres intelligents",hi:"🕓 Historique",pr:"Appuyez sur le bouton",clr:"✕ effacer",sf:"Filtres",jp:"Prochain jackpot"},fi:{g:"🧠 GENEROI",nd:"🕐 Seuraava arvonta",ld:"📊 Viimeiset arvonnat",fil:"Suodattimet",hi:"🕓 Historia",pr:"Paina nappia",clr:"✕ tyhjennä",sf:"Suodattimet",jp:"Seuraava jackpot"},et:{g:"🧠 GENEREERI",nd:"🕐 Järgmine loos",ld:"📊 Viimased loosimised",fil:"Filtrid",hi:"🕓 Ajalugu",pr:"Vajuta nuppu",clr:"✕ tühjenda",sf:"Filtrid",jp:"Järgmine jackpot"},hr:{g:"🧠 GENERIRAJ",nd:"🕐 Sljedeće izvlačenje",ld:"📊 Posljednja izvlačenja",fil:"Filtri",hi:"🕓 Povijest",pr:"Pritisni gumb",clr:"✕ obriši",sf:"Filtri",jp:"Sljedeći jackpot"},is:{g:"🧠 BÚA TIL",nd:"🕐 Næsta dráttur",ld:"📊 Síðustu dráttir",fil:"Síar",hi:"🕓 Saga",pr:"Ýttu á hnappinn",clr:"✕ hreinsa",sf:"Síar",jp:"Næsti jackpot"},no:{g:"🧠 GENERER",nd:"🕐 Neste trekking",ld:"📊 Siste trekkinger",fil:"Filtre",hi:"🕓 Historikk",pr:"Trykk på knappen",clr:"✕ slett",sf:"Filtre",jp:"Neste jackpot"},sv:{g:"🧠 GENERERA",nd:"🕐 Nästa dragning",ld:"📊 Senaste dragningar",fil:"Filter",hi:"🕓 Historik",pr:"Tryck på knappen",clr:"✕ rensa",sf:"Filter",jp:"Nästa jackpot"},lv:{g:"🧠 ĢENERĒT",nd:"🕐 Nākamā izloze",ld:"📊 Pēdējās izlozes",fil:"Filtri",hi:"🕓 Vēsture",pr:"Nospiediet pogu",clr:"✕ notīrīt",sf:"Filtri",jp:"Nākamais džekpots"},lt:{g:"🧠 GENERUOTI",nd:"🕐 Kitas traukimas",ld:"📊 Paskutiniai traukimai",fil:"Filtrai",hi:"🕓 Istorija",pr:"Paspauskite mygtuką",clr:"✕ išvalyti",sf:"Filtrai",jp:"Kitas džekpotas"},cs:{g:"🧠 GENEROVAT",nd:"🕐 Příští losování",ld:"📊 Poslední losování",fil:"Filtry",hi:"🕓 Historie",pr:"Stiskněte tlačítko",clr:"✕ vymazat",sf:"Filtry",jp:"Příští jackpot"},hu:{g:"🧠 GENERÁLÁS",nd:"🕐 Következő sorsolás",ld:"📊 Legutóbbi sorsolások",fil:"Szűrők",hi:"🕓 Előzmények",pr:"Nyomja meg a gombot",clr:"✕ törlés",sf:"Szűrők",jp:"Következő jackpot"},sk:{g:"🧠 GENEROVAŤ",nd:"🕐 Ďalšie žrebovanie",ld:"📊 Posledné žrebovania",fil:"Filtre",hi:"🕓 História",pr:"Stlačte tlačidlo",clr:"✕ vymazať",sf:"Filtre",jp:"Ďalší jackpot"},sl:{g:"🧠 GENERIRAJ",nd:"🕐 Naslednje žrebanje",ld:"📊 Zadnja žrebanja",fil:"Filtri",hi:"🕓 Zgodovina",pr:"Pritisni gumb",clr:"✕ izbriši",sf:"Filtri",jp:"Naslednji jackpot"},el:{g:"🧠 ΔΗΜΙΟΥΡΓΙΑ",nd:"🕐 Επόμενη κλήρωση",ld:"📊 Τελευταίες κληρώσεις",fil:"Φίλτρα",hi:"🕓 Ιστορικό",pr:"Πατήστε το κουμπί",clr:"✕ καθαρισμός",sf:"Φίλτρα",jp:"Επόμενο τζάκποτ"}};
const FL={pl:["Brak sekwencji 3+","Rozrzut ≥18","2–3 parzyste","≥1 liczba >31","Suma 110–160","Sektory hot","Brak dubl euro"],en:["No sequence 3+","Spread ≥18","2–3 even","≥1 number >31","Sum 110–160","Hot sectors","No euro double"],nl:["Geen reeks 3+","Spreiding ≥18","2–3 even","≥1 getal >31","Som 110–160","Hete sectoren","Geen dubbel"],de:["Keine Sequenz 3+","Streuung ≥18","2–3 gerade","≥1 Zahl >31","Summe 110–160","Hot-Sektoren","Kein Duplikat"],es:["Sin secuencia 3+","Dispersión ≥18","2–3 pares","≥1 número >31","Suma 110–160","Sectores calientes","Sin doble"],it:["Nessuna sequenza","Dispersione ≥18","2–3 pari","≥1 numero >31","Somma 110–160","Settori caldi","Nessun doppio"],fr:["Pas de séquence","Écart ≥18","2–3 pairs","≥1 numéro >31","Somme 110–160","Secteurs chauds","Pas de double"],fi:["Ei sekvenssiä 3+","Hajonta ≥18","2–3 parillista","≥1 luku >31","Summa 110–160","Kuumat sektorit","Ei euro-tupla"],et:["Ei jada 3+","Hajuvus ≥18","2–3 paaris","≥1 arv >31","Summa 110–160","Kuumad sektorid","Ei euro-topelt"],hr:["Bez niza 3+","Raspon ≥18","2–3 parnih","≥1 broj >31","Zbroj 110–160","Vrući sektori","Bez euro-dupla"],is:["Engin röð 3+","Dreifing ≥18","2–3 sléttar","≥1 tala >31","Summa 110–160","Heitir geirar","Engin tvítekning"],no:["Ingen sekvens 3+","Spredning ≥18","2–3 partall","≥1 tall >31","Sum 110–160","Varme sektorer","Ingen euro-dobbel"],sv:["Ingen sekvens 3+","Spridning ≥18","2–3 jämna","≥1 tal >31","Summa 110–160","Varma sektorer","Ingen euro-dubbel"],lv:["Nav virknes 3+","Izkliede ≥18","2–3 pāra","≥1 skaitlis >31","Summa 110–160","Karstie sektori","Nav euro-dubulta"],lt:["Nėra sekos 3+","Sklaida ≥18","2–3 lyginiai","≥1 skaičius >31","Suma 110–160","Karšti sektoriai","Nėra euro-dvigubo"],cs:["Žádná sekvence 3+","Rozptyl ≥18","2–3 sudá","≥1 číslo >31","Součet 110–160","Horké sektory","Žádný euro-duplikát"],hu:["Nincs sorozat 3+","Szórás ≥18","2–3 páros","≥1 szám >31","Összeg 110–160","Forró szektorok","Nincs euro-dupla"],sk:["Žiadna sekvencia 3+","Rozptyl ≥18","2–3 párne","≥1 číslo >31","Súčet 110–160","Horúce sektory","Žiadny euro-duplikát"],sl:["Brez zaporedja 3+","Razpon ≥18","2–3 sode","≥1 število >31","Vsota 110–160","Vroči sektorji","Brez euro-dvojnika"],el:["Χωρίς ακολουθία 3+","Εύρος ≥18","2–3 ζυγά","≥1 αριθμός >31","Άθροισμα 110–160","Ζεστοί τομείς","Χωρίς euro-διπλό"]};
const FB=[{k:"noSeq",d:true},{k:"spread",d:true},{k:"even",d:true},{k:"high",d:true},{k:"sum",d:true},{k:"hot",d:false},{k:"euro",d:true}];
const SD=[{date:"10.03.2026",main:[2,3,17,18,28],euro:[4,10],jp:"€15,276,748"},{date:"06.03.2026",main:[8,17,26,31,47],euro:[1,6],jp:"€10,000,000"},{date:"03.03.2026",main:[1,9,14,35,49],euro:[2,10],jp:"€10,000,000"}];
const FD={pl:[{n:"Brak sekwencji 3+",d:"Eliminuje kombinacje gdzie 3+ liczb idzie po kolei np. 5,6,7."},{n:"Rozrzut ≥18",d:"Różnica między najmniejszą a największą liczbą musi wynosić co najmniej 18."},{n:"2–3 parzyste",d:"W zestawie muszą być dokładnie 2 lub 3 liczby parzyste."},{n:"≥1 liczba >31",d:"Co najmniej jedna liczba musi być większa niż 31."},{n:"Suma 110–160",d:"Suma wszystkich 5 liczb musi być między 110 a 160."},{n:"Sektory hot",d:"Co najmniej 2 liczby z sektorów 1–10 lub 31–40. Filtr opcjonalny."},{n:"Brak dubl euro",d:"Liczby Euro są różne od siebie."}],en:[{n:"No sequence 3+",d:"Eliminates combinations where 3+ numbers are consecutive e.g. 5,6,7."},{n:"Spread ≥18",d:"The difference between smallest and largest number must be at least 18."},{n:"2–3 even",d:"The set must contain exactly 2 or 3 even numbers."},{n:"≥1 number >31",d:"At least one number must be greater than 31."},{n:"Sum 110–160",d:"The sum of all 5 numbers must be between 110 and 160."},{n:"Hot sectors",d:"At least 2 numbers from sectors 1–10 or 31–40. Optional filter."},{n:"No euro double",d:"Euro numbers are different from each other."}]};
const MC={pl:"✕ Zamknij",en:"✕ Close",nl:"✕ Sluiten",de:"✕ Schließen",es:"✕ Cerrar",it:"✕ Chiudi",fr:"✕ Fermer",fi:"✕ Sulje",et:"✕ Sulge",hr:"✕ Zatvori",is:"✕ Loka",no:"✕ Lukk",sv:"✕ Stäng",lv:"✕ Aizvērt",lt:"✕ Uždaryti",cs:"✕ Zavřít",hu:"✕ Bezárás",sk:"✕ Zavrieť",sl:"✕ Zapri",el:"✕ Κλείσιμο"};
const MT={pl:"📋 FILTRY INFO",en:"📋 FILTERS INFO",nl:"📋 FILTERS INFO",de:"📋 FILTER INFO",es:"📋 INFO FILTROS",it:"📋 INFO FILTRI",fr:"📋 INFO FILTRES",fi:"📋 SUODATTIMET INFO",et:"📋 FILTRID INFO",hr:"📋 FILTRI INFO",is:"📋 SÍAR INFO",no:"📋 FILTRE INFO",sv:"📋 FILTER INFO",lv:"📋 FILTRI INFO",lt:"📋 FILTRAI INFO",cs:"📋 FILTRY INFO",hu:"📋 SZŰRŐK INFO",sk:"📋 FILTRE INFO",sl:"📋 FILTRI INFO",el:"📋 ΦΊΛΤΡΑ INFO"};
let lang="pl",fil={},hist=[],tries=0,DRAWS=[...SD];
FB.forEach(f=>fil[f.k]=f.d);
const p2=n=>String(n).padStart(2,"0");
function ball(n,gold,size=44){const d=document.createElement("div");d.className="ball "+(gold?"ball-gold":"ball-blue");d.style.width=d.style.height=size+"px";d.style.fontSize=size>36?"0.85rem":"0.62rem";d.textContent=p2(n);return d;}
function renderLangs(){const el=document.getElementById("langs");el.innerHTML="";Object.entries(LANGS).forEach(([c,i])=>{const b=document.createElement("button");b.className="lang-btn"+(lang===c?" active":"");b.textContent=i.flag+" "+i.n;b.onclick=()=>{lang=c;renderAll()};el.appendChild(b);});}
function renderFilters(){const el=document.getElementById("filters");el.innerHTML="";FB.forEach((f,i)=>{const b=document.createElement("button");b.className="fil-btn "+(fil[f.k]?"fil-on":"fil-off");b.innerHTML=(fil[f.k]?"✅":"⚠️")+" "+FL[lang][i];b.onclick=()=>{fil[f.k]=!fil[f.k];renderAll()};el.appendChild(b);});}
function renderDraws(){const el=document.getElementById("draws");el.innerHTML="";DRAWS.forEach(dr=>{const div=document.createElement("div");div.className="draw";const hdr=document.createElement("div");hdr.className="draw-header";hdr.innerHTML=`<span class="draw-date">📅 ${dr.date}</span><span class="draw-jp">${dr.jp}</span>`;div.appendChild(hdr);const balls=document.createElement("div");balls.className="balls";dr.main.forEach(n=>balls.appendChild(ball(n,true,30)));const sep=document.createElement("div");sep.className="sep";balls.appendChild(sep);dr.euro.forEach(n=>balls.appendChild(ball(n,false,30)));div.appendChild(balls);el.appendChild(div);});}
function renderHistory(){const box=document.getElementById("hist-box");const el=document.getElementById("history");if(!hist.length){box.style.display="none";return;}box.style.display="block";el.innerHTML="";hist.forEach(h=>{const row=document.createElement("div");row.className="hist-row";h.main.forEach(n=>row.appendChild(ball(n,true,26)));const sep=document.createElement("span");sep.style.color="#2e3d55";sep.textContent="|";row.appendChild(sep);h.euro.forEach(n=>row.appendChild(ball(n,false,26)));const sum=document.createElement("span");sum.className="hist-sum";sum.textContent="Σ"+h.sum;row.appendChild(sum);el.appendChild(row);});}
function renderTexts(){const t=T[lang];document.getElementById("cd-lbl").textContent=t.nd;document.getElementById("gen-btn").textContent=t.g;document.getElementById("fil-lbl").textContent=t.fil;document.getElementById("ld-lbl").textContent=t.ld;document.getElementById("hist-lbl").textContent=t.hi;document.getElementById("clr-btn").textContent=t.clr;document.getElementById("s-fil-lbl").textContent=t.sf;document.getElementById("jackpot-lbl").textContent="🏆 "+t.jp;const p=document.getElementById("press-txt");if(p)p.textContent=t.pr;}
function renderStats(){document.getElementById("s-tries").textContent=tries;document.getElementById("s-fil").textContent=Object.values(fil).filter(Boolean).length+"/7";}
function renderAll(){renderLangs();renderFilters();renderDraws();renderHistory();renderTexts();renderStats();}
function nextDraw(){const now=new Date();for(let d=0;d<=7;d++){const t=new Date(now);t.setDate(now.getDate()+d);t.setHours(20,0,0,0);if([2,5].includes(t.getDay())&&t>now)return t;}}
setInterval(()=>{const dr=nextDraw();if(!dr)return;const df=dr-new Date();document.getElementById("countdown").textContent=Math.floor(df/86400000)+"d "+p2(Math.floor((df%86400000)/3600000))+"h "+p2(Math.floor((df%3600000)/60000))+"m "+p2(Math.floor((df%60000)/1000))+"s";},1000);
function rM(){const s=new Set();while(s.size<5)s.add(Math.floor(Math.random()*50)+1);return[...s].sort((a,b)=>a-b)}
function rE(){const s=new Set();while(s.size<2)s.add(Math.floor(Math.random()*12)+1);return[...s].sort((a,b)=>a-b)}
function chk(m){for(let i=0;i<m.length-2;i++)if(fil.noSeq&&m[i+1]===m[i]+1&&m[i+2]===m[i]+2)return false;if(fil.spread&&m[4]-m[0]<18)return false;if(fil.even){const e=m.filter(n=>n%2===0).length;if(e<2||e>3)return false}if(fil.high&&!m.some(n=>n>31))return false;if(fil.sum){const s=m.reduce((a,b)=>a+b,0);if(s<110||s>160)return false}if(fil.hot&&m.filter(n=>n<=10||(n>=31&&n<=40)).length<2)return false;return true;}
document.getElementById("gen-btn").onclick=()=>{let m,e,a=0;do{m=rM();e=rE();a++}while(!chk(m)&&a<10000);const sum=m.reduce((a,b)=>a+b,0);tries++;hist.unshift({main:m,euro:e,sum});if(hist.length>5)hist.pop();const box=document.getElementById("result-box");box.innerHTML="";const bd=document.createElement("div");bd.className="balls";m.forEach(n=>bd.appendChild(ball(n,true,44)));const sep=document.createElement("div");sep.className="sep";bd.appendChild(sep);e.forEach(n=>bd.appendChild(ball(n,false,44)));box.appendChild(bd);const info=document.createElement("div");info.className="res-info";info.textContent="Σ "+sum+(a>1?" • "+a+" prób":" • ✓");box.appendChild(info);document.getElementById("s-sum").textContent=sum;document.getElementById("s-sum").style.color="#e0e8ff";renderStats();renderHistory();};
document.getElementById("clr-btn").onclick=()=>{hist=[];tries=0;renderAll()};
function openModal(){const desc=FD[lang]||FD.en;document.getElementById("modal-title").textContent=MT[lang]||"📋 FILTERS INFO";document.getElementById("modal-close").textContent=MC[lang]||"✕ Close";const c=document.getElementById("modal-content");c.innerHTML="";desc.forEach(item=>{const div=document.createElement("div");div.className="modal-item";div.innerHTML=`<div class="modal-item-name">✅ ${item.n}</div><div class="modal-item-desc">${item.d}</div>`;c.appendChild(div);});document.getElementById("modal-overlay").classList.add("open");document.body.style.overflow="hidden";}
function closeModal(){document.getElementById("modal-overlay").classList.remove("open");document.body.style.overflow="";}
function closeModalOutside(e){if(e.target===document.getElementById("modal-overlay"))closeModal();}
async function fetchLive(){
  try{
    const r=await fetch("https://api.anthropic.com/v1/messages",{method:"POST",headers:{"Content-Type":"application/json"},body:JSON.stringify({model:"claude-sonnet-4-20250514",max_tokens:1000,tools:[{type:"web_search_20250305",name:"web_search"}],system:'Return ONLY valid JSON no markdown: {"draws":[{"date":"DD.MM.YYYY","main":[n1,n2,n3,n4,n5],"euro":[e1,e2],"jp":"€X,XXX,XXX"}],"nextJackpot":"€XX,000,000"}',messages:[{role:"user",content:"Search for last 3 Eurojackpot results and next jackpot amount. JSON only."}]})});
    const data=await r.json();
    const hasToolUse=data.content&&data.content.some(i=>i.type==="tool_use");
    let txt="";
    if(hasToolUse){
      const r2=await fetch("https://api.anthropic.com/v1/messages",{method:"POST",headers:{"Content-Type":"application/json"},body:JSON.stringify({model:"claude-sonnet-4-20250514",max_tokens:800,tools:[{type:"web_search_20250305",name:"web_search"}],system:'Return ONLY valid JSON no markdown: {"draws":[{"date":"DD.MM.YYYY","main":[n1,n2,n3,n4,n5],"euro":[e1,e2],"jp":"€X,XXX,XXX"}],"nextJackpot":"€XX,000,000"}',messages:[{role:"user",content:"Search for last 3 Eurojackpot results and next jackpot. JSON only."},{role:"assistant",content:data.content},{role:"user",content:data.content.filter(i=>i.type==="tool_use").map(i=>({type:"tool_result",tool_use_id:i.id,content:"Use the search results to build the JSON."}))}]})});
      const d2=await r2.json();
      txt=d2.content.filter(i=>i.type==="text").map(i=>i.text).join("\n");
    }else{
      txt=data.content.filter(i=>i.type==="text").map(i=>i.text).join("\n");
    }
    const m=txt.replace(/```json|```/g,"").match(/\{[\s\S]*\}/);
    if(!m)throw new Error("no json");
    const p=JSON.parse(m[0]);
    if(p.draws&&p.draws.length){DRAWS.length=0;p.draws.slice(0,3).forEach(d=>DRAWS.push(d));renderDraws();}
    if(p.nextJackpot)document.getElementById("jackpot-val").textContent=p.nextJackpot;
  }catch(e){DRAWS=[...SD];renderDraws();document.getElementById("jackpot-val").textContent="€22,000,000";}
}
renderAll();
fetchLive();
</script>
</body>
</html>
