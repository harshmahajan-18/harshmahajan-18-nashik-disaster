<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="description" content="Shelters, hospitals, safe routes and emergency help for Nashik district.">
<meta name="theme-color" content="#c25e00">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Nashik DisasterGuard</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.9.4/leaflet.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Mukta:wght@400;600;700&family=Yatra+One&display=swap" rel="stylesheet">
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#f6f3ee;--panel:#fff;--line:#ddd5c8;--tx:#1b2330;--mut:#5b6675;--sf:#c25e00;--on:#fff;--rv:#0b7285;--ok:#1f8a5b;--lim:#a67c00;--full:#c0392b}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0d1420;--panel:#16202f;--line:#2a374a;--tx:#e8edf4;--mut:#93a1b5;--sf:#ff9d2e;--on:#1b1200;--rv:#3fb7c9;--ok:#4cc38a;--lim:#f2c230;--full:#ef5b5b}}
:root[data-theme="dark"]{--bg:#0d1420;--panel:#16202f;--line:#2a374a;--tx:#e8edf4;--mut:#93a1b5;--sf:#ff9d2e;--on:#1b1200;--rv:#3fb7c9;--ok:#4cc38a;--lim:#f2c230;--full:#ef5b5b}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--tx);font:400 16px/1.5 Mukta,system-ui,sans-serif}
.wrap{max-width:1100px;margin:0 auto;padding:0 16px 40px}
.top{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:18px 0 8px;flex-wrap:wrap}
h1{font:400 clamp(28px,5vw,42px)/1.1 "Yatra One",Georgia,serif;margin:0;color:var(--sf)}
.top p{margin:2px 0 0;color:var(--mut)}
.sos{background:var(--full);color:#fff;text-decoration:none;font-weight:700;padding:12px 20px;border-radius:999px;font-size:18px}
a:focus-visible,button:focus-visible{outline:3px solid var(--rv);outline-offset:2px}
.note{background:var(--panel);border-left:4px solid var(--lim);padding:8px 12px;margin:8px 0 16px;color:var(--mut);font-size:14px}
.modes{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:12px}
.modes button,.chips button{font:inherit;border:1px solid var(--line);background:var(--panel);color:var(--tx);padding:8px 14px;border-radius:999px;cursor:pointer}
.modes button[aria-selected=true],.chips button[aria-pressed=true]{background:var(--sf);border-color:var(--sf);color:var(--on);font-weight:700}
.card{background:var(--panel);border:1px solid var(--line);border-radius:10px;padding:16px}
#alert h2{margin:0 0 4px;font-size:20px}
#alert p.a{margin:0 0 12px;font-weight:600}
.dd{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.dd h3{margin:0 0 4px;font-size:15px}
.dd ul{margin:0;padding-left:18px;color:var(--mut)}
.main{display:grid;grid-template-columns:1.1fr 1fr;gap:16px;margin-top:16px}
.stats{display:flex;gap:20px;margin-bottom:10px}
.stats b{font-size:26px;display:block;line-height:1}
.stats span{color:var(--mut);font-size:13px}
.chips{display:flex;gap:6px;flex-wrap:wrap;margin:8px 0}
.chips button{padding:5px 11px;font-size:14px}
#list{max-height:430px;overflow:auto;display:grid;gap:8px}
.it{border:1px solid var(--line);border-radius:8px;padding:8px 10px;cursor:pointer;background:transparent;text-align:left;font:inherit;color:inherit;width:100%}
.it[aria-current=true]{border-color:var(--rv);box-shadow:0 0 0 2px var(--rv)}
.it b{display:block}.it small{color:var(--mut)}
.st{font-weight:700;font-size:13px}
.Open{color:var(--ok)}.Limited{color:var(--lim)}.Full{color:var(--full)}
#det{margin-bottom:8px;min-height:84px}
#det a{color:var(--rv);font-weight:700}
svg#map{width:100%;height:auto;display:block;background:color-mix(in srgb,var(--rv) 7%,var(--panel));border-radius:8px}
.leg{display:flex;gap:12px;flex-wrap:wrap;font-size:13px;color:var(--mut);margin-top:8px}
.leg i{display:inline-block;width:10px;height:10px;border-radius:50%;margin-right:4px}
h2.s{font:400 24px "Yatra One",Georgia,serif;margin:28px 0 10px}
.ct{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:10px}
.ct a{display:block;text-decoration:none;color:var(--tx);border:1px solid var(--line);background:var(--panel);border-radius:8px;padding:10px 12px}
.ct b{display:block;font-size:26px;color:var(--full)}
.ck{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:6px}
.ck label{display:flex;gap:8px;align-items:center;padding:6px 8px;border:1px solid var(--line);border-radius:8px;background:var(--panel)}
.bar{height:8px;background:var(--line);border-radius:4px;overflow:hidden;margin:6px 0 12px}
.bar div{height:100%;background:var(--ok);width:0}
footer{margin-top:32px;color:var(--mut);font-size:13px}
@media (max-width:860px){.main,.dd{grid-template-columns:1fr}}
.lgb{font:inherit;border:1px solid var(--line);background:var(--panel);color:var(--tx);border-radius:999px;padding:8px 14px;cursor:pointer;margin-right:8px}
.top>div:last-child{display:flex;align-items:center}
.two{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.f{display:grid;gap:8px;align-content:start}
input,select,textarea{font:inherit;color:var(--tx);background:var(--bg);border:1px solid var(--line);border-radius:8px;padding:8px}
.f button,#ask{font:inherit;font-weight:700;background:var(--rv);color:var(--on);border:0;border-radius:8px;padding:9px 14px;cursor:pointer}
#chat{max-height:240px;overflow:auto;display:grid;gap:6px;margin-bottom:10px}
.m{white-space:pre-line;margin:0;padding:8px 12px;border-radius:12px;max-width:85%}
.m.b{background:var(--bg);border:1px solid var(--line)}
.m.u{background:var(--sf);color:var(--on);justify-self:end}
.row{display:flex;gap:8px}.row input{flex:1;min-width:0}
.ent{border-top:1px solid var(--line);padding:6px 0}
@media (max-width:860px){.two{grid-template-columns:1fr}}
details{border-top:1px solid var(--line);padding:8px 0}details:first-child{border-top:0}
summary{cursor:pointer;font-weight:700}details p{margin:6px 0 0;color:var(--mut)}
#locs a{color:var(--rv);font-weight:700}
@media print{#modes,#alert,.main,.two,.np,.sos,.lgb,#chat,.row,button,.note,h2[data-t=ask]{display:none!important}body{background:#fff;color:#000}.card,.ct a{border-color:#999}}
#map{height:520px;border-radius:8px;position:relative;z-index:0}
.hm{width:22px;height:22px;background:#0b7285;color:#fff;font:700 13px/18px sans-serif;text-align:center;border:2px solid #fff;border-radius:4px}
@media (max-width:860px){#map{height:400px}}
.wrap{padding-bottom:96px}
html{scroll-behavior:smooth}@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
.qb{position:fixed;left:0;right:0;bottom:0;z-index:5;display:flex;gap:8px;align-items:center;overflow-x:auto;background:var(--panel);border-top:1px solid var(--line);padding:8px 12px calc(8px + env(safe-area-inset-bottom,0px))}
.qb a,.qb button{flex:none;font:inherit;font-size:14px;border:1px solid var(--line);background:var(--bg);color:var(--tx);border-radius:999px;padding:6px 12px;text-decoration:none;cursor:pointer}
#stat{margin-left:auto;color:var(--mut)}
#dock.dock{position:fixed;right:12px;bottom:68px;width:min(380px,calc(100vw - 24px));max-height:55vh;overflow:auto;z-index:6;background:var(--bg);border:1px solid var(--line);border-radius:12px;padding:0 12px 12px;box-shadow:0 8px 30px rgba(0,0,0,.3)}
#dock.dock h2.s{margin:12px 0 8px;font-size:18px}
@media print{.qb,#dock.dock{display:none!important}}
.ph{display:block;max-width:100%;max-height:160px;border-radius:8px;margin:6px 0}
.pl{display:grid;gap:4px;font-size:14px;color:var(--mut)}
</style>
</head>
<body>
<div class="wrap">
<noscript><p class="note">This page needs JavaScript. Emergency numbers: 112 all emergencies, 108 ambulance, 101 fire, 100 police.</p></noscript>
<header class="top">
 <div><h1>नाशिक आपत्ती सहाय्य</h1><p data-t="sub">Nashik DisasterGuard: shelters, safe routes and help for Nashik and nearby towns</p></div>
 <div><button id="th" class="lgb">Theme</button><button id="lang" class="lgb">मराठी</button><a class="sos" href="tel:112" data-t="sos">SOS: call 112</a></div>
</header>
<p class="note" data-t="note">Demo data. Shelter status, capacity and alerts are illustrative and map positions are approximate. Confirm with the Nashik district control room or Nashik Municipal Corporation before relying on them.</p>

<p id="sm" class="note"></p>
<div class="modes" role="tablist" aria-label="Emergency type" id="modes"></div>
<section class="card" id="alert"></section>

<div class="main">
 <section class="card">
  <p id="mw" class="note" hidden>The map background could not load, so you only see the markers. This usually means the page is open inside a preview that blocks outside images, or you are offline. Download this file and open it in Chrome, or host it on GitHub Pages.</p>
  <div id="map" role="application" aria-label="Map of Nashik district with shelters, hospitals and hazard zones"></div>
  <div class="leg"><span><i style="background:var(--ok)"></i>Open</span><span><i style="background:var(--lim)"></i>Limited</span><span><i style="background:var(--full)"></i>Full</span><span><i style="background:var(--rv);border-radius:2px"></i>Hospital</span><span><i style="background:var(--full);opacity:.35"></i>Hazard zone</span></div>
 </section>
 <section class="card">
  <div class="stats" id="stats"></div>
  <p id="gw" class="note" hidden></p>
  <div id="det" aria-live="polite"></div>
  <div class="chips" id="chips"></div>
  <div id="list"></div>
 </section>
</div>

<h2 class="s" data-t="num">Emergency numbers</h2>
<div class="ct">
 <a href="tel:112"><b>112</b>All emergencies</a>
 <a href="tel:108"><b>108</b>Ambulance</a>
 <a href="tel:101"><b>101</b>Fire brigade</a>
 <a href="tel:100"><b>100</b>Police</a>
 <a href="tel:1070"><b>1070</b>State disaster helpline</a>
</div>
<p class="note" style="margin-top:10px">Add the Nashik district control room number here after confirming it on the Collector office website.</p>
<h3 style="margin:16px 0 8px">Hospitals</h3><div class="ct" id="hos"></div>

<h2 class="s" data-t="kit">Emergency kit</h2>
<div id="pct">Ready: 0%</div><div class="bar"><div id="fill"></div></div>
<div class="ck" id="ck"></div>

<h2 class="s">Safety tools</h2>
<div class="two">
<section class="card f"><h3 style="margin:0">Share my location</h3><p style="margin:0">Send your position to family with a map link.</p><button id="gl">Get my location link</button><small id="locs" style="color:var(--mut)"></small></section>
<section class="card f"><h3 style="margin:0">Signal for help</h3><p style="margin:0">Flashes the screen and sounds a siren so rescuers can see and hear you. Avoid if flashing lights bother you.</p><button id="sig">Start signal</button></section>
</div>
<div class="np"><h2 class="s">Request supplies to my location</h2>
<form id="freq" class="card f"><div class="ck" id="items"><label><input type="checkbox" name="item" value="Drinking water"> Drinking water</label><label><input type="checkbox" name="item" value="Food packets"> Food packets</label><label><input type="checkbox" name="item" value="Medicines"> Medicines</label><label><input type="checkbox" name="item" value="Baby food and milk"> Baby food and milk</label><label><input type="checkbox" name="item" value="Blankets"> Blankets</label><label><input type="checkbox" name="item" value="Torch and power bank"> Torch and power bank</label><label><input type="checkbox" name="item" value="Sanitary items"> Sanitary items</label></div>
<div class="row"><button type="button" id="alli">Select all</button></div>
<input name="n" type="number" min="1" placeholder="Number of people">
<input name="to" inputmode="tel" placeholder="Relief contact phone number to send this to">
<textarea name="note" rows="2" placeholder="Address, landmark, floor, special needs"></textarea>
<button>Use my location and prepare request</button><div id="rq" aria-live="polite"></div>
<small style="color:var(--mut)">This prepares a message with your location and sends it to the number you enter. It does not place an order or dispatch anyone: a person at that number must receive it and act. If a life is in danger, call 112 or 108.</small></form></div>
<h2 class="s">Family safety plan</h2>
<form id="fam" class="card f"><input name="m1" placeholder="Meeting point near home"><input name="m2" placeholder="Meeting point outside your area"><input name="ct" placeholder="Out-of-town contact: name and number"><textarea name="mem" rows="3" placeholder="Family members: names, ages, medicines, special needs"></textarea><div class="row"><button>Save plan</button><button type="button" id="pr">Print kit and plan</button><button type="button" data-dl>Download sheet</button></div><small id="fs" style="color:var(--mut)">Saved only in this browser.</small></form>
<h2 class="s">First aid and flood depth</h2>
<div class="card" id="fa">
<details><summary>Heavy bleeding</summary><p>Press firmly with a clean cloth. If it soaks through, add more cloth on top instead of removing it. Raise the injured limb if you can and call 108.</p></details>
<details><summary>Someone pulled from water</summary><p>Never enter fast water yourself. Throw a rope or a float. Call 108. If the person is not breathing, start CPR if you are trained; the 108 operator can guide you.</p></details>
<details><summary>Broken bone</summary><p>Keep the limb still in the position you found it. Don't try to straighten it. Support it with padding and get medical help.</p></details>
<details><summary>Electric shock during floods</summary><p>Switch off the main supply if you can do it safely and dry. Don't touch the person or standing water. Move them with a dry wooden stick if needed, then call 108.</p></details>
<details><summary>Cold and wet</summary><p>Move indoors, replace wet clothes with dry ones, wrap in blankets, and give a warm sweet drink if the person is awake and alert.</p></details>
<details><summary>How deep is too deep?</summary><p>About 15 cm (ankle) of moving water can knock a person down. About 30 cm can float many small cars. About 60 cm can carry away most vehicles. If you can't see the road under the water, turn around.</p></details>
</div>
<div class="np"><h2 class="s">Volunteer sign-up</h2>
<form id="fvol" class="card f"><input name="name" required placeholder="Name / नाव"><input name="ph" required placeholder="Phone number"><select name="sk" aria-label="Skill"><option>First aid</option><option>Swimming or boat rescue</option><option>Driving</option><option>Food and supplies</option><option>Translation</option></select><input name="loc" required placeholder="Your area"><label class="pl">Photo (optional, stays on this device)<input type="file" name="photo" accept="image/*"></label><button>Sign up</button><small style="color:var(--mut)">Saved only in this browser. A real deployment would send this to the local control room.</small><div id="lvol"></div></form></div>
<div id="dock"><h2 class="s" data-t="ask">Ask the helper</h2>
<section class="card"><div id="chat" aria-live="polite"></div><div class="row"><input id="q" aria-label="Your question" placeholder="Nearest shelter, hospital, flood, Kumbh... / विचारा"><button id="ask">Ask</button></div><small style="color:var(--mut)">Simple keyword helper, not AI. In danger, call 112.</small></section></div>
<div class="two">
<div><h2 class="s" data-t="rep">Community reports</h2>
<form id="frep" class="card f"><select name="type" aria-label="Type"><option>Road</option><option>Flood</option><option>Shelter</option><option>Medical</option><option>Rescue</option></select><input name="loc" required placeholder="Location / ठिकाण"><select name="sev" aria-label="Severity"><option>Low</option><option>Medium</option><option>High</option><option>Critical</option></select><textarea name="desc" rows="2" placeholder="What do you see? / काय दिसत आहे?"></textarea><label class="pl">Photo (optional, stays on this device)<input type="file" name="photo" accept="image/*"></label><button>Save report</button><small style="color:var(--mut)">Saved on this device only. Not sent to any authority. In an emergency call 112.</small><div id="lrep"></div></form><div id="lpub"></div></div>
<div><h2 class="s" data-t="reg">Register rescued people</h2>
<form id="freg" class="card f"><input name="name" required placeholder="Name / नाव"><input name="age" type="number" min="0" max="120" placeholder="Age / वय"><input name="loc" required placeholder="Found at / ठिकाण"><select name="cond" aria-label="Condition"><option>Stable</option><option>Needs medical</option><option>Critical</option></select><label class="pl">Photo (optional, stays on this device)<input type="file" name="photo" accept="image/*"></label><button>Save entry</button><small style="color:var(--mut)">Saved on this device only, for volunteers to coordinate. Keep personal details minimal.</small><div id="lreg"></div></form></div>
</div>
<footer>Built for Nashik and nearby areas: Trimbakeshwar, Igatpuri, Sinnar, Niphad, Dindori and Malegaon. Sample data, not an official service. Entries are stored only in your browser.</footer>
</div>

<nav class="qb" aria-label="Quick actions"><a href="#map">Map</a><button id="dk">Dock helper</button><a href="#fam">Family plan</a><a href="#frep">Report</a><a href="#freg">Rescue</a><a href="#fvol">Volunteer</a><button id="qs">Signal</button><button data-dl>Download sheet</button><button id="stat">Location off</button></nav>
<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.9.4/leaflet.js"></script>
<script>
/* Paste your free Web3Forms access key here (see SETUP-FORMS.md). Leave as is for local-only mode. */
const SHEET_URL="https://script.google.com/macros/s/AKfycbzzFgJHJzgqf3qJ-qrbffOnNWYEN-gJXyrD0tPN0AAs/dev",SITE_KEY="SAVE";   /* Google Sheet backend with the approve/reject website */
const FORM_KEY="PASTE_ACCESS_KEY";                       /* or: the simpler email-only option */
const VIA_SHEET=!SHEET_URL.startsWith("PASTE");
const SHEET_ON=VIA_SHEET||!FORM_KEY.startsWith("PASTE");
const S=[
["Nashik Road Municipal Hall","Nashik Road",19.9500,73.8330,800,"Open",1,1],
["CIDCO Community Hall","CIDCO, Nashik",19.9680,73.7550,500,"Open",0,1],
["College Road Municipal School","College Road, Nashik",20.0010,73.7600,350,"Limited",0,1],
["Satpur MIDC Hall","Satpur, Nashik",20.0000,73.7300,450,"Open",1,0],
["Deolali Camp School","Deolali Camp",19.9330,73.8350,400,"Open",0,1],
["Gangapur Road ZP School","Gangapur Road, Nashik",20.0150,73.7450,300,"Full",0,0],
["Trimbakeshwar Gram Panchayat Hall","Trimbakeshwar",19.9322,73.5305,300,"Open",1,1,"Trimbak"],
["Igatpuri ZP School","Igatpuri",19.6955,73.5622,350,"Limited",1,1,"Igatpuri"],
["Sinnar Tehsil Hall","Sinnar",19.8450,74.0000,500,"Open",0,1,"Sinnar"],
["Niphad Community Hall","Niphad",20.0833,74.1167,450,"Open",1,0,"Niphad"],
["Dindori ZP School","Dindori",20.2000,73.8300,300,"Limited",0,1,"Dindori"],
["Malegaon Municipal Hall","Malegaon",20.5500,74.5300,700,"Open",1,1,"Malegaon"]];
const H=[["Civil Hospital, Nashik",19.9990,73.7760],["Rural Hospital, Trimbakeshwar",19.9300,73.5330],["Sub-District Hospital, Igatpuri",19.6930,73.5600],["Sub-District Hospital, Sinnar",19.8500,73.9950],["Civil Hospital, Malegaon",20.5530,74.5250]];
const Z=[["Ramkund and Panchavati ghats",20.0063,73.7922,22],["Godavari below Gangapur Dam",20.0450,73.7000,20],["Kasara ghat",19.6500,73.5600,22]];
const R=[[19.93,73.53],[19.97,73.65],[20.0,73.79],[20.03,73.9],[20.08,74.05],[20.09,74.13]];
const M={
flood:{n:"Godavari flood",a:"Dam releases can raise the Godavari fast. Stay off Ramkund, Panchavati and riverbank roads when water rises.",d:["Move to higher ground early, such as the Nashik Road or CIDCO side","Follow Nashik Municipal Corporation and police announcements","Carry documents, medicines and a charged phone"],x:["Don't cross flooded causeways or bridges","Don't go to the ghats to watch or take photos","Don't drive through low-lying roads and underpasses"]},
crowd:{n:"Kumbh crowd safety",a:"Simhastha 2027 will bring very large crowds. Use the marked entry and exit lanes at the ghats.",d:["Agree a family meeting point before you enter","Follow police and volunteer barricade directions","Write your phone number on children's wrists or clothes"],x:["Don't push or move against the crowd flow","Don't stop on bridges or in narrow lanes","Don't rush toward a ghat after a gate closes"]},
slide:{n:"Ghat landslide",a:"Heavy rain can bring rockfall on Kasara ghat and the Trimbakeshwar hill roads.",d:["Slow down and watch for fresh mud, stones or cracks","Stop in a wide safe spot and call 112 if the road is blocked","Move away from the slope if you hear rumbling"],x:["Don't park under cliffs or loose slopes","Don't cross a blocked stretch on foot","Don't drive ghat roads at night in heavy rain"]},
road:{n:"Road accident",a:"Crashes on the Mumbai–Agra highway, the Samruddhi Expressway and ghat sections need a fast, clear call for help.",d:["Switch on hazard lights and move to safety","Call 112 or 108 with the road name and nearest landmark","Keep the injured person still unless there is fire risk"],x:["Don't move someone with a neck or back injury","Don't crowd the scene","Don't give food or water to a badly injured person"]}};
const K=["Drinking water (3 litres per person per day)","Dry food for 3 days","Regular medicines and a first aid kit","Torch and spare batteries","Power bank and charging cable","Copies of ID and key documents","Cash in small notes","Whistle","Blanket and a change of clothes","Family meeting point agreed"];
const $=s=>document.querySelector(s);
let sel=0,flt="all",me=null,mode="flood",wid=null,acc=0,first=1;
const P=(la,lo)=>[20+(lo-73.4)/1.3*560,20+(20.65-la)/1.1*520];
function km(a,b,c,d){const r=Math.PI/180,x=(d-b)*r*Math.cos((a+c)*r/2),y=(c-a)*r;return Math.hypot(x,y)*6371}
const col=s=>({Open:"var(--ok)",Limited:"var(--lim)",Full:"var(--full)"}[s]);
function dist(s){return me?km(me[0],me[1],s[2],s[3]):null}
function modes(){$("#modes").innerHTML=Object.keys(M).map(k=>`<button role="tab" data-m="${k}" aria-selected="${k==mode}">${(lang?MR[k]:M[k]).n}</button>`).join("");
 const m=lang?MR[mode]:M[mode];$("#alert").innerHTML=`<h2>${m.n}</h2><p class="a">${m.a}</p><div class="dd"><div><h3>${lang?"करा":"Do"}</h3><ul>${m.d.map(t=>`<li>${t}</li>`).join("")}</ul></div><div><h3>${lang?"टाळा":"Avoid"}</h3><ul>${m.x.map(t=>`<li>${t}</li>`).join("")}</ul></div></div>`}
let LM=null,LL=null,ls=0,fit=0;
const COL={Open:"#1f8a5b",Limited:"#d9a400",Full:"#c0392b"};
function map(){
 if(!window.L){$("#map").innerHTML="<p style='padding:16px'>The map could not load. Check your internet connection and reload.</p>";return}
 if(!LM){
  LM=L.map("map").setView([20.0,73.79],10);
  const esri=L.tileLayer("https://server.arcgisonline.com/ArcGIS/rest/services/World_Street_Map/MapServer/tile/{z}/{y}/{x}",{maxZoom:19,attribution:"Tiles &copy; Esri"}),
  osm=L.tileLayer("https://tile.openstreetmap.org/{z}/{x}/{y}.png",{maxZoom:19,attribution:"&copy; OpenStreetMap contributors"}),
  sat=L.tileLayer("https://server.arcgisonline.com/ArcGIS/rest/services/World_Imagery/MapServer/tile/{z}/{y}/{x}",{maxZoom:19,attribution:"Tiles &copy; Esri"});
  [esri,osm,sat].forEach(t=>t.on("tileerror",()=>{$("#mw").hidden=false}).on("tileload",()=>{$("#mw").hidden=true}));
  esri.addTo(LM);L.control.layers({"Streets":esri,"OpenStreetMap":osm,"Satellite":sat}).addTo(LM);
  Z.forEach(z=>L.circle([z[1],z[2]],{radius:z[3]*50,color:"#c0392b",weight:1,fillColor:"#c0392b",fillOpacity:.25}).bindTooltip("Hazard zone: "+z[0]).addTo(LM));
  H.forEach(h=>L.marker([h[1],h[2]],{icon:L.divIcon({className:"",html:'<div class="hm">H</div>',iconSize:[22,22],iconAnchor:[11,11]})}).bindTooltip(h[0]).addTo(LM));
  LL=L.layerGroup().addTo(LM);
  setTimeout(()=>LM.invalidateSize(),300)}
 LL.clearLayers();
 S.forEach((s,i)=>L.circleMarker([s[2],s[3]],{radius:i==sel?12:8,color:i==sel?"#111":"#fff",weight:i==sel?3:2,fillColor:COL[s[5]],fillOpacity:1}).bindTooltip(s[0]+", "+s[5]).on("click",()=>{sel=i;map();side()}).addTo(LL));
 if(ls!==sel){ls=sel;LM.panTo([S[sel][2],S[sel][3]])}
 if(me){
  if(acc)L.circle(me,{radius:acc,color:"#ff9d2e",weight:1,fillColor:"#ff9d2e",fillOpacity:.15,interactive:false}).addTo(LL);
  L.circleMarker(me,{radius:7,color:"#fff",weight:2,fillColor:"#ff9d2e",fillOpacity:1}).bindTooltip("You are here").addTo(LL);
  if(wid!==null)L.circleMarker(me,{radius:15,fill:false,color:"#ff9d2e",weight:2,interactive:false}).addTo(LL);
  if(!fit){fit=1;LM.fitBounds([me,[S[sel][2],S[sel][3]]],{padding:[40,40],maxZoom:14})}
 }else fit=0}
function side(){const op=S.filter(s=>s[5]!="Full");$("#stats").innerHTML=`<div><b>${op.length}</b><span>shelters with space</span></div><div><b>${op.reduce((a,s)=>a+s[4],0)}</b><span>places available</span></div><div><b>${H.length}</b><span>hospitals shown</span></div>`;
 const f=[["all","All"],["Open","Open"],["med","Medical"],["food","Food"]];$("#chips").innerHTML=f.map(c=>`<button data-f="${c[0]}" aria-pressed="${flt==c[0]}">${c[1]}</button>`).join("")+`<button id="loc">Find nearest to me</button><button id="live" aria-pressed="${wid!==null}">${wid!==null?"Stop live location":"Live location"}</button>${gpsTxt()}`;
 let L=S.map((s,i)=>[s,i]).filter(([s])=>flt=="all"||(flt=="med"?s[6]:flt=="food"?s[7]:s[5]==flt));
 if(me)L.sort((a,b)=>dist(a[0])-dist(b[0]));
 $("#list").innerHTML=L.map(([s,i])=>`<button class="it" data-i="${i}" aria-current="${i==sel}"><b>${s[0]}</b><small>${s[1]}${me?", "+dist(s).toFixed(1)+" km away":""}</small><br><span class="st ${s[5]}">${s[5]}</span> <small>Capacity ${s[4]}${s[6]?", medical":""}${s[7]?", food":""}</small></button>`).join("")||"<p>No shelters match this filter.</p>";
 const s=S[sel];$("#det").innerHTML=`<b>${s[0]}</b><br>${s[1]}. <span class="st ${s[5]}">${s[5]}</span>, capacity ${s[4]}.${me?`<br>${dist(s).toFixed(1)} km in a straight line, about ${wk(dist(s))} min on foot (estimate).`:""}<br><a href="https://www.google.com/maps/dir/?api=1&destination=${s[2]},${s[3]}" target="_blank" rel="noopener">Get directions</a>`}
function all(){modes();map();side()}
document.addEventListener("click",e=>{const t=e.target;
 const m=t.closest("[data-m]");if(m){mode=m.dataset.m;modes();return}
 const f=t.closest("[data-f]");if(f){flt=f.dataset.f;side();return}
 const i=t.closest("[data-i]");if(i){sel=+i.dataset.i;map();side();return}
 if(t.id=="live"){live();return}
 if(t.id=="loc"){t.disabled=true;
  getFix(a=>{t.textContent="Finding you... about "+a+" m"}).then(p=>{setFix(p);pickNearest();map();side()},e=>alert(locErr(e))).finally(()=>{t.disabled=false})}});
let ck={};try{ck=JSON.parse(localStorage.getItem("ngd-ck")||"{}")}catch(e){}
function kit(){$("#ck").innerHTML=K.map((k,i)=>`<label><input type="checkbox" data-k="${i}" ${ck[i]?"checked":""}> ${k}</label>`).join("");prog()}
function prog(){const n=K.filter((_,i)=>ck[i]).length,p=Math.round(n/K.length*100);$("#pct").textContent=(lang?"तयारी: ":"Ready: ")+p+"%";$("#fill").style.width=p+"%"}
$("#ck").addEventListener("change",e=>{ck[e.target.dataset.k]=e.target.checked;try{localStorage.setItem("ngd-ck",JSON.stringify(ck))}catch(x){}prog()});
let lang=0;
const MR={
flood:{n:"गोदावरी पूर",a:"धरणातून पाणी सोडल्यास गोदावरीची पातळी झपाट्याने वाढू शकते. पाणी वाढत असताना रामकुंड, पंचवटी आणि नदीकाठच्या रस्त्यांपासून दूर रहा.",d:["लवकर उंच ठिकाणी जा, उदा. नाशिक रोड किंवा सिडको परिसर","महापालिका आणि पोलिसांच्या सूचनांचे पालन करा","कागदपत्रे, औषधे आणि चार्ज केलेला फोन सोबत ठेवा"],x:["पाण्याखालील पूल किंवा रस्ते ओलांडू नका","घाटावर पाहण्यासाठी किंवा फोटोसाठी जाऊ नका","सखल रस्ते आणि अंडरपासमधून गाडी चालवू नका"]},
crowd:{n:"कुंभ गर्दी सुरक्षा",a:"सिंहस्थ २०२७ मध्ये प्रचंड गर्दी अपेक्षित आहे. घाटांवर ठरवलेल्या प्रवेश आणि निर्गमन मार्गांचाच वापर करा.",d:["आत जाण्यापूर्वी कुटुंबाचे भेटण्याचे ठिकाण ठरवा","पोलीस आणि स्वयंसेवकांच्या सूचनांचे पालन करा","मुलांच्या कपड्यांवर तुमचा फोन नंबर लिहा"],x:["धक्काबुक्की करू नका, गर्दीच्या उलट दिशेने जाऊ नका","पूल आणि अरुंद गल्ल्यांमध्ये थांबू नका","गेट बंद झाल्यावर घाटाकडे धावू नका"]},
slide:{n:"घाटात दरड कोसळणे",a:"जोरदार पावसात कसारा घाट आणि त्र्यंबकेश्वर घाट रस्त्यांवर दरड कोसळू शकते.",d:["वेग कमी करा; ताजा चिखल, दगड किंवा भेगा पहा","रस्ता बंद असल्यास सुरक्षित जागी थांबून ११२ वर कॉल करा","गडगडाट ऐकू आल्यास उतारापासून दूर जा"],x:["कडे किंवा सैल उतारांखाली गाडी उभी करू नका","बंद भाग पायी ओलांडू नका","जोरदार पावसात रात्री घाटात गाडी चालवू नका"]},
road:{n:"रस्ते अपघात",a:"मुंबई–आग्रा महामार्ग, समृद्धी महामार्ग आणि घाट भागातील अपघातांसाठी स्पष्ट माहिती देऊन तातडीने मदत मागवा.",d:["हॅझार्ड लाईट सुरू करा आणि सुरक्षित जागी जा","रस्त्याचे नाव आणि जवळची खूण सांगून ११२ किंवा १०८ वर कॉल करा","आग लागण्याचा धोका नसल्यास जखमीला हलवू नका"],x:["मान किंवा पाठीला दुखापत असल्यास हलवू नका","घटनास्थळी गर्दी करू नका","गंभीर जखमीला अन्न किंवा पाणी देऊ नका"]}};
const T={sub:["Nashik DisasterGuard: shelters, safe routes and help for Nashik and nearby towns","नाशिक डिझास्टरगार्ड: नाशिक आणि जवळच्या शहरांसाठी निवारे, सुरक्षित मार्ग आणि मदत"],
sos:["SOS: call 112","SOS: ११२ वर कॉल करा"],
note:[$(".note").innerHTML,"डेमो माहिती. निवाऱ्यांची स्थिती, क्षमता आणि सूचना केवळ उदाहरणादाखल आहेत; नकाशावरील जागा अंदाजे आहेत. वापरण्यापूर्वी नाशिक जिल्हा नियंत्रण कक्ष किंवा महापालिकेकडे खात्री करा."],
num:["Emergency numbers","आपत्कालीन क्रमांक"],kit:["Emergency kit","आपत्कालीन किट"],ask:["Ask the helper","मदतनीसला विचारा"],rep:["Community reports","स्थानिक नोंदी"],reg:["Register rescued people","वाचवलेल्यांची नोंद"]};
function setLang(){document.documentElement.lang=lang?"mr":"en";document.querySelectorAll("[data-t]").forEach(e=>e.innerHTML=T[e.dataset.t][lang]);$("#lang").textContent=lang?"English":"मराठी";modes();prog()}
$("#lang").onclick=()=>{lang=1-lang;setLang()};
function ans(q){q=q.toLowerCase();const o=S.filter(s=>s[5]!="Full");if(me)o.sort((a,b)=>dist(a)-dist(b));const h=r=>r.test(q);
if(h(/shelter|camp|निवार|आश्रय/))return (lang?"जागा असलेले निवारे: ":"Shelters with space: ")+o.slice(0,3).map(s=>s[0]).join(", ")+(lang?". अंतरासाठी \"Find nearest to me\" वापरा.":". Use \"Find nearest to me\" for distances.");
if(h(/hospital|doctor|medical|रुग्णालय|दवाखाना|डॉक्टर/))return (lang?"रुग्णालये: ":"Hospitals: ")+H.map(x=>x[0]).join("; ")+(lang?". रुग्णवाहिका: १०८.":". Ambulance: 108.");
const k=h(/flood|river|godavari|पूर|गोदावरी/)?"flood":h(/kumbh|crowd|stampede|कुंभ|गर्दी/)?"crowd":h(/landslide|ghat|rock|दरड|घाट/)?"slide":h(/accident|crash|अपघात/)?"road":0;
if(k){const m=lang?MR[k]:M[k];return m.a+" "+m.d[0]+"."}
if(h(/number|call|police|fire|ambulance|क्रमांक|पोलीस/))return lang?"११२ सर्व आपत्कालीन, १०८ रुग्णवाहिका, १०१ अग्निशमन, १०० पोलीस.":"112 all emergencies, 108 ambulance, 101 fire, 100 police.";
return lang?"मी निवारे, रुग्णालये, पूर, कुंभ गर्दी, घाट आणि अपघातांबद्दल सांगू शकतो. धोक्यात असल्यास ११२ वर कॉल करा.":"I can help with shelters, hospitals, floods, Kumbh crowds, ghats and accidents. In danger, call 112."}
function say(c,t){const p=document.createElement("p");p.className="m "+c;p.textContent=t;$("#chat").append(p);$("#chat").scrollTop=1e5;return p}
function go(){const q=$("#q").value.trim();if(!q)return;$("#q").value="";say("u",q);say("b",ans(q))}
$("#ask").onclick=go;$("#q").onkeydown=e=>{if(e.key=="Enter")go()};
say("b","Hi, ask me about shelters, hospitals, floods, Kumbh crowds or accidents. नमस्कार, निवारे, रुग्णालये किंवा पुराबद्दल विचारा.");
const esc=s=>String(s).replace(/[&<>"]/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c]));
function log(key,fid,lid,fmt){let a=[];try{a=JSON.parse(localStorage.getItem(key)||"[]")}catch(e){}
const draw=()=>{$(lid).innerHTML=a.map(fmt).join("")||"<small style='color:var(--mut)'>No entries yet.</small>"};
const sv=()=>{try{localStorage.setItem(key,JSON.stringify(a));return 1}catch(x){return 0}};
 $(fid).addEventListener("submit",async e=>{e.preventDefault();const fd=new FormData(e.target),f={};fd.forEach((v,k)=>{if(!(v instanceof File))f[k]=v});
  const ph=fd.get("photo");f.img=ph instanceof File&&ph.size?await shrink(ph):"";f.t=new Date().toLocaleString();toSheet(key,f);a.unshift(f);a=a.slice(0,30);
  let note="";if(!sv()&&f.img){f.img="";note="Photo was too large to save, so this entry was saved without it.";sv()}
  e.target.reset();draw();if(note)$(lid).insertAdjacentHTML("afterbegin","<small>"+note+"</small>")});draw()}
function shrink(file){return new Promise(res=>{const rd=new FileReader();rd.onerror=()=>res("");rd.onload=()=>{const im=new Image();im.onerror=()=>res("");im.onload=()=>{const k=Math.min(1,480/Math.max(im.width,im.height)),c=document.createElement("canvas");c.width=Math.round(im.width*k);c.height=Math.round(im.height*k);c.getContext("2d").drawImage(im,0,0,c.width,c.height);res(c.toDataURL("image/jpeg",.6))};im.src=rd.result};rd.readAsDataURL(file)})}
const pic=r=>r.img?`<img class="ph" src="${r.img}" alt="Attached photo">`:"";
log("ngd-rep","#frep","#lrep",r=>`<div class="ent"><b>${esc(r.type)}, ${esc(r.sev)}</b>: ${esc(r.loc)}<br>${esc(r.desc)}<br>${pic(r)}<small>${esc(r.t)}</small></div>`);
log("ngd-reg","#freg","#lreg",r=>`<div class="ent"><b>${esc(r.name)}</b>${r.age?", "+esc(r.age):""}: ${esc(r.loc)}<br>${esc(r.cond)} <small>${esc(r.t)}</small>${pic(r)}</div>`);
$("#hos").innerHTML=H.map(h=>`<a href="https://www.google.com/maps/dir/?api=1&destination=${h[1]},${h[2]}" target="_blank" rel="noopener"><b style="font-size:16px;color:var(--rv)">${h[0]}</b>Get directions</a>`).join("");
$("#th").onclick=()=>{const d=document.documentElement,k=d.dataset.theme?d.dataset.theme=="dark":matchMedia("(prefers-color-scheme:dark)").matches;d.dataset.theme=k?"light":"dark"};
$("#gl").onclick=async()=>{const out=$("#locs"),msg=()=>{const t="I need help. My location: https://maps.google.com/?q="+me[0].toFixed(6)+","+me[1].toFixed(6)+" (GPS accuracy about "+acc+" m, "+new Date(fixT).toLocaleTimeString()+")"+(acc>100?". GPS is weak, please call me.":""),e=encodeURIComponent(t);
  out.innerHTML=`<a href="https://wa.me/?text=${e}" target="_blank" rel="noopener">Send on WhatsApp</a> &nbsp; <a href="sms:?&body=${e}">Send by SMS</a><br>${esc(t)}`};
 if(fresh()){msg();return}
 if(!navigator.geolocation){out.textContent=locErr();return}
 out.textContent="Finding your position...";
 try{setFix(await getFix(a=>{out.textContent="Improving accuracy... about "+a+" m"}));map();side();msg()}catch(e){out.textContent=locErr(e)}};
let sg=null;
$("#sig").onclick=()=>{if(sg){sg();return}const ov=document.createElement("div");ov.style.cssText="position:fixed;inset:0;z-index:9;display:grid;place-items:center;font:700 28px Mukta,sans-serif;cursor:pointer";ov.textContent="Tap to stop";document.body.append(ov);let on=0;
 const iv=setInterval(()=>{on=!on;ov.style.background=on?"#fff":"#c00";ov.style.color=on?"#c00":"#fff"},400);let ac,os,fv;
 try{ac=new(window.AudioContext||window.webkitAudioContext)();os=ac.createOscillator();os.type="square";const g=ac.createGain();g.gain.value=.15;os.connect(g);g.connect(ac.destination);os.start();fv=setInterval(()=>{os.frequency.value=os.frequency.value==880?660:880},500)}catch(e){}
 sg=()=>{clearInterval(iv);clearInterval(fv);try{os.stop();ac.close()}catch(e){}ov.remove();sg=null;$("#sig").textContent="Start signal"};ov.onclick=sg;$("#sig").textContent="Stop signal"};
const FK=["m1","m2","ct","mem"];let fm={};try{fm=JSON.parse(localStorage.getItem("ngd-fam")||"{}")}catch(e){}
FK.forEach(k=>{$("#fam").elements[k].value=fm[k]||""});
$("#fam").addEventListener("submit",e=>{e.preventDefault();FK.forEach(k=>fm[k]=e.target.elements[k].value);try{localStorage.setItem("ngd-fam",JSON.stringify(fm));$("#fs").textContent="Plan saved in this browser."}catch(x){$("#fs").textContent="Could not save in this browser."}});
$("#pr").onclick=()=>print();
log("ngd-vol","#fvol","#lvol",r=>`<div class="ent"><b>${esc(r.name)}</b>, ${esc(r.sk)}: ${esc(r.loc)}, ${esc(r.ph)}${pic(r)}</div>`);
let fixT=0;
const quality=a=>a<=20?"good":a<=100?"fair":"poor",wk=d=>Math.round(d*16),fresh=()=>me&&acc&&acc<=100&&Date.now()-fixT<30000;
const gpsTxt=()=>acc?`<small>${wid!==null?"Live":"Last fix"}: accuracy about ${acc} m (${quality(acc)})</small>`:"";
function pickNearest(){const o=S.map((s,i)=>[dist(s),i]).sort((a,b)=>a[0]-b[0]);sel=(o.find(x=>S[x[1]][5]!="Full")||o[0])[1]}
function setFix(p){me=[p.coords.latitude,p.coords.longitude];acc=Math.round(p.coords.accuracy);fixT=Date.now();
 const far=km(me[0],me[1],20.0,73.79)>150,g=$("#gw");g.hidden=!(far||acc>100);
 g.textContent=far?"You seem to be far from Nashik, so distances are to Nashik district shelters.":"GPS is weak (about "+acc+" m). Move to open sky or near a window, and add a landmark in your notes."}
function locErr(e){return !navigator.geolocation?"Location is not available on this device.":!window.isSecureContext&&location.protocol!="file:"?"Location needs a secure (https) page.":e&&e.code==1?"Location permission was denied. Allow location access in your browser settings and try again.":"Could not get a GPS fix. Go outside or near a window, turn on GPS, and try again."}
// Keeps the most accurate reading for a few seconds: one quick reading is often a coarse network guess.
function getFix(onProg,ms=10000,good=20){return new Promise((res,rej)=>{
 if(!navigator.geolocation)return rej({code:0});
 let best=null,done=false,id,tm;
 const end=err=>{if(done)return;done=true;clearTimeout(tm);navigator.geolocation.clearWatch(id);best?res(best):rej(err||{code:3})};
 tm=setTimeout(()=>end(),ms);
 id=navigator.geolocation.watchPosition(p=>{if(!best||p.coords.accuracy<best.coords.accuracy)best=p;if(onProg)onProg(Math.round(best.coords.accuracy));if(p.coords.accuracy<=good)end()},e=>end(e),{enableHighAccuracy:true,maximumAge:0,timeout:ms});
 if(done)navigator.geolocation.clearWatch(id)})}
function live(){
 if(wid!==null){navigator.geolocation.clearWatch(wid);wid=null;first=1;$("#gw").hidden=true;map();side();return}
 if(!navigator.geolocation){alert(locErr());return}
 wid=navigator.geolocation.watchPosition(p=>{const a=p.coords.accuracy;
  if(me&&acc&&a>acc*3&&a>50&&Date.now()-fixT<20000)return; // ignore a much worse reading right after a good one
  const mv=me?km(me[0],me[1],p.coords.latitude,p.coords.longitude)*1000:1e9;
  if(mv<3&&Math.abs(a-acc)<5){fixT=Date.now();return} // standing still: skip GPS jitter
  setFix(p);if(first){first=0;pickNearest()}map();side()},
 e=>{if(e.code==1){wid=null;first=1;map();side();alert(locErr(e))}else{const g=$("#gw");g.hidden=false;g.textContent="Waiting for a GPS signal. Go outside or near a window."}},
 {enableHighAccuracy:true,maximumAge:0,timeout:30000});
 side()}
function dlSheet(){const g=k=>$("#fam").elements[k].value,L=["NASHIK EMERGENCY SHEET","Saved: "+new Date().toLocaleString(),"Sample data. Confirm shelters with the Nashik district control room before relying on it.","","EMERGENCY NUMBERS","112 all emergencies","108 ambulance","101 fire","100 police","1070 state disaster helpline","","FAMILY PLAN","Meeting point near home: "+g("m1"),"Meeting point outside area: "+g("m2"),"Out-of-town contact: "+g("ct"),"Family members: "+g("mem"),"","KIT CHECKLIST"];
 K.forEach((k,i)=>L.push((ck[i]?"[x] ":"[ ] ")+k));
 L.push("","SHELTERS");S.forEach(x=>L.push(x[0]+" ("+x[1]+"), "+x[5]+", capacity "+x[4]+(x[6]?", medical":"")+(x[7]?", food":"")+": https://maps.google.com/?q="+x[2]+","+x[3]));
 L.push("","HOSPITALS");H.forEach(h=>L.push(h[0]+": https://maps.google.com/?q="+h[1]+","+h[2]));
 const a=document.createElement("a");a.href=URL.createObjectURL(new Blob([L.join("\r\n")],{type:"text/plain"}));a.download="nashik-emergency-sheet.txt";document.body.append(a);a.click();a.remove();setTimeout(()=>URL.revokeObjectURL(a.href),1000)}
document.querySelectorAll("[data-dl]").forEach(b=>b.onclick=dlSheet);
$("#alli").onclick=()=>document.querySelectorAll("#items input").forEach(x=>x.checked=true);
try{$("#freq").elements.to.value=localStorage.getItem("ngd-to")||""}catch(e){}
$("#freq").addEventListener("submit",e=>{e.preventDefault();const f=e.target,items=[...f.querySelectorAll("input[name=item]:checked")].map(x=>x.value);
 if(!items.length){$("#rq").textContent="Choose at least one item.";return}
 const build=(la,lo)=>{const t=`SUPPLY REQUEST
Need: ${items.join(", ")}
People: ${f.elements.n.value||"not given"}
Note: ${f.elements.note.value||"none"}
My location: https://maps.google.com/?q=${la},${lo}${acc?" (GPS accuracy about "+acc+" m"+(acc>100?", weak: please confirm the landmark":"")+")":""}
Sent: ${new Date().toLocaleString()}`,q=encodeURIComponent(t);let num=f.elements.to.value.replace(/\D/g,"");if(num.length==10)num="91"+num;
  try{localStorage.setItem("ngd-to",f.elements.to.value)}catch(x){}
  pushSheet({type:"request",items:items.join(", "),n:f.elements.n.value||"",note:f.elements.note.value||"",lat:la,lon:lo,acc:acc||0});
  $("#rq").innerHTML=`<p style="white-space:pre-line;margin:6px 0">${esc(t)}</p><a href="https://wa.me/${num}?text=${q}" target="_blank" rel="noopener">Send on WhatsApp</a> &nbsp; <a href="sms:${num}?&body=${q}">Send by SMS</a>${SHEET_ON?"<p>Also being sent to the control room.</p>":""}`};
 if(fresh())return build(me[0],me[1]);
 if(!navigator.geolocation){$("#rq").textContent=locErr();return}
 $("#rq").textContent="Finding your position...";
 getFix(a=>{$("#rq").textContent="Improving accuracy... about "+a+" m"}).then(p=>{setFix(p);map();side();build(me[0],me[1])},e=>{$("#rq").textContent=locErr(e)+" You can still write your address in the note."})});
const _side=side;side=function(){_side();updStat()};
function updStat(){const e=$("#stat");if(!me){e.textContent="Location off";e.removeAttribute("data-i");return}
 const o=S.map((s,i)=>[dist(s),i]).filter(x=>S[x[1]][5]!="Full").sort((a,b)=>a[0]-b[0])[0];if(!o)return;
 const age=Math.round((Date.now()-fixT)/1000),stale=wid!==null&&age>30?" (no update for "+age+" s)":"";
 e.dataset.i=o[1];e.textContent=(wid!==null?"Live: ":"Last fix: ")+S[o[1]][0]+", "+o[0].toFixed(1)+" km, about "+wk(o[0])+" min walk"+(acc?", ±"+acc+" m":"")+stale}
setInterval(()=>{if(wid!==null)updStat()},5000);
addEventListener("resize",()=>{if(LM)LM.invalidateSize()});
$("#dk").onclick=()=>{const d=$("#dock");d.classList.toggle("dock");$("#dk").textContent=d.classList.contains("dock")?"Undock helper":"Dock helper"};
$("#qs").onclick=()=>$("#sig").click();
updStat();
all();kit();setLang();
let Q=[];try{Q=JSON.parse(localStorage.getItem("ngd-outbox")||"[]")}catch(e){}
const keepQ=()=>{try{localStorage.setItem("ngd-outbox",JSON.stringify(Q))}catch(e){}};
let busy=false;
function fmt(it){const o={Received:it.t};
 if(it.type=="report")Object.assign(o,{Type:it.rtype,Severity:it.sev,Location:it.loc,Description:it.desc,"Moderation line":JSON.stringify({ngd:"report",id:it.id,t:it.t,type:it.rtype,sev:it.sev,loc:it.loc,desc:it.desc})});
 if(it.type=="rescue")Object.assign(o,{Name:it.name,Age:it.age,"Found at":it.loc,Condition:it.cond});
 if(it.type=="volunteer")Object.assign(o,{Name:it.name,Phone:it.ph,Skill:it.sk,Area:it.loc});
 if(it.type=="request")Object.assign(o,{Items:it.items,People:it.n,Note:it.note,"Map link":"https://maps.google.com/?q="+it.lat+","+it.lon,"GPS accuracy (m)":it.acc});
 if(it.img)o.Photo="The sender has a photo; it stays on their phone.";
 return o}
const KINDS={report:"Community report",rescue:"Rescued person",volunteer:"Volunteer sign-up",request:"SUPPLY REQUEST"};
async function flush(){if(busy||!SHEET_ON)return;busy=true;
 try{while(Q.length){const it=Q[0];if(VIA_SHEET){await fetch(SHEET_URL,{method:"POST",mode:"no-cors",headers:{"Content-Type":"text/plain"},body:JSON.stringify({...it,key:SITE_KEY})});Q.shift();keepQ();continue}
  const r=await fetch("https://api.web3forms.com/submit",{method:"POST",headers:{"Content-Type":"application/json",Accept:"application/json"},body:JSON.stringify({access_key:FORM_KEY,subject:"Nashik DisasterGuard: "+KINDS[it.type],from_name:"Nashik DisasterGuard",botcheck:"",...fmt(it)})});
  if(r.status>=500||r.status==429)throw 0;
  if(r.status>=400){$("#sm").textContent="Could not send to the control room. Check the access key in the page."}
  Q.shift();keepQ()}}catch(e){}
 busy=false}
function pushSheet(item){if(!SHEET_ON)return;Q.push({...item,t:new Date().toLocaleString()});if(Q.length>50)Q.shift();keepQ();flush()}
function toSheet(key,f){const m={"ngd-rep":{type:"report",id:Date.now().toString(36)+Math.random().toString(36).slice(2,6),rtype:f.type,sev:f.sev,loc:f.loc,desc:f.desc},"ngd-reg":{type:"rescue",name:f.name,age:f.age,loc:f.loc,cond:f.cond},"ngd-vol":{type:"volunteer",name:f.name,ph:f.ph,sk:f.sk,loc:f.loc}}[key];if(m){m.img=f.img||"";pushSheet(m)}}
function renderPub(){const a=window.APPROVED||[];
 $("#lpub").innerHTML="<h3 style='margin:12px 0 4px'>Verified reports</h3>"+(a.length?a.slice(0,20).map(x=>`<div class="ent"><b>${esc(x.type)}, ${esc(x.sev)}</b>: ${esc(x.loc)}<br>${esc(x.desc)}<br><small>Verified by the control room. Reported ${esc(x.t)}</small></div>`).join(""):"<small>No verified reports yet.</small>")}
function loadPub(){
 if(VIA_SHEET){fetch(SHEET_URL+"?key="+encodeURIComponent(SITE_KEY)).then(r=>r.json()).then(j=>{window.APPROVED=j.reports||[];renderPub()}).catch(renderPub);return}
const el=document.createElement("script");el.src="approved.js?ts="+Date.now();el.onload=el.onerror=renderPub;document.head.append(el)}
loadPub();if(VIA_SHEET)setInterval(loadPub,60000);
addEventListener("online",flush);
$("#sm").textContent=VIA_SHEET?"Sending is on: new entries go to the control room. Reports appear publicly after approval.":SHEET_ON?"Sending is on: new entries are emailed to the control room. Photos stay on the sender's phone.":"Local mode: entries are saved only on this phone. Add your Web3Forms access key to send them to the control room.";
if(SHEET_ON){$("#frep>small").textContent="Sent to the control room. It shows publicly only after the control room approves it. The photo stays on this phone. Don't include phone numbers. In an emergency call 112.";$("#freg>small").textContent="Sent to the control room (text only) and kept on this phone. Take photos only with consent.";$("#fvol>small").textContent="Sent to the control room and kept on this phone.";flush()}
if(VIA_SHEET){$("#frep>small").textContent="Sent to the control room. It shows publicly only after approval. Don't include phone numbers. In an emergency call 112.";$("#freg>small").textContent="Sent to the control room and kept on this phone. Take photos only with consent."}
</script>
</body>
</html>
