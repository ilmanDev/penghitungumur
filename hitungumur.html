<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Penghitung Umur By. Ilman</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<style>
:root{
--bg:#fff;--text:#222;--card:#f1f5f9;--primary:#6366f1;
}
body.dark{
--bg:#0f172a;--text:#f8fafc;--card:#1e293b;
}
body{
margin:0;min-height:100vh;
display:flex;justify-content:center;align-items:center;
background:var(--bg);color:var(--text);
font-family:Arial,sans-serif;
transition:.3s;
}
.container{
background:var(--card);
padding:25px;border-radius:16px;
width:100%;max-width:420px;
box-shadow:0 15px 30px rgba(0,0,0,.3);
animation:fade .8s ease;
}
@keyframes fade{from{opacity:0;transform:translateY(20px)}to{opacity:1}}
.top{display:flex;justify-content:space-between;margin-bottom:15px}
button{
border:none;border-radius:10px;
padding:10px 14px;
background:var(--primary);color:#fff;
cursor:pointer;transition:.2s;
}
button:hover{transform:scale(1.08)}
h1{text-align:center}
.author{text-align:center;font-size:14px;opacity:.7;margin-bottom:15px}
input{
width:100%;padding:10px;border-radius:8px;
border:none;margin-bottom:15px
}
.result{
margin-top:20px;
display:flex;justify-content:space-around;
font-weight:bold;text-align:center;
animation:glow .8s ease;
}
@keyframes glow{
0%{box-shadow:0 0 0 transparent}
50%{box-shadow:0 0 25px var(--primary)}
100%{box-shadow:0 0 0 transparent}
}
.box{
background:rgba(0,0,0,.1);
padding:12px;border-radius:12px;
min-width:90px;
animation:bounce .6s ease;
}
@keyframes bounce{
0%{transform:scale(.5)}
60%{transform:scale(1.1)}
100%{transform:scale(1)}
}
.number{
font-size:26px;color:var(--primary)
}
.confetti{
position:fixed;
width:10px;height:10px;
background:var(--primary);
top:-10px;
animation:fall 2s linear forwards;
}
@keyframes fall{
to{transform:translateY(110vh) rotate(360deg);opacity:0}
}
</style>
</head>
<body>

<div class="container">
<div class="top">
<button onclick="toggleTheme();soundClick()"><i class="fas fa-moon"></i></button>
<button onclick="changeLang();soundClick()"><i class="fas fa-language"></i></button>
</div>

<h1 id="title">Penghitung Umur</h1>
<div class="author">By. Ilman</div>

<label id="lbl">Tanggal Lahir</label>
<input type="date" id="birth">

<button style="width:100%" onclick="calcAge()">
<i class="fas fa-calculator"></i> <span id="btn">Hitung Umur</span>
</button>

<div class="result" id="result" style="display:none">
<div class="box"><div class="number" id="y">0</div><div id="yt">Tahun</div></div>
<div class="box"><div class="number" id="m">0</div><div id="mt">Bulan</div></div>
<div class="box"><div class="number" id="d">0</div><div id="dt">Hari</div></div>
</div>
</div>

<script>
/* ===== SOUND ENGINE ===== */
const audioCtx = new (window.AudioContext||window.webkitAudioContext)();
function beep(freq,dur){
const osc=audioCtx.createOscillator();
const gain=audioCtx.createGain();
osc.frequency.value=freq;
osc.connect(gain);
gain.connect(audioCtx.destination);
osc.start();
gain.gain.exponentialRampToValueAtTime(0.0001,audioCtx.currentTime+dur);
osc.stop(audioCtx.currentTime+dur);
}
function soundClick(){beep(600,.1)}
function soundResult(){beep(300,.3);setTimeout(()=>beep(500,.2),200)}

/* ===== LANGUAGE ===== */
let lang=0;
const L=[
{t:"Penghitung Umur",l:"Tanggal Lahir",b:"Hitung Umur",y:"Tahun",m:"Bulan",d:"Hari",dir:"ltr"},
{t:"Age Calculator",l:"Birth Date",b:"Calculate Age",y:"Years",m:"Months",d:"Days",dir:"ltr"},
{t:"Calculadora de Edad",l:"Fecha de Nacimiento",b:"Calcular Edad",y:"Años",m:"Meses",d:"Días",dir:"ltr"},
{t:"حاسبة العمر",l:"تاريخ الميلاد",b:"احسب العمر",y:"سنة",m:"شهر",d:"يوم",dir:"rtl"},
{t:"年齢計算機",l:"生年月日",b:"年齢を計算",y:"年",m:"月",d:"日",dir:"ltr"}
];

function animate(id,val){
let i=0;
const el=document.getElementById(id);
const int=setInterval(()=>{
el.innerText=i;
if(i>=val)clearInterval(int);
i++;
},25);
}

/* ===== CONFETTI ===== */
function confetti(){
for(let i=0;i<25;i++){
const c=document.createElement("div");
c.className="confetti";
c.style.left=Math.random()*100+"vw";
c.style.background=`hsl(${Math.random()*360},80%,60%)`;
document.body.appendChild(c);
setTimeout(()=>c.remove(),2000);
}
}

function calcAge(){
soundClick();
const b=new Date(birth.value);
if(!b.getTime())return;
const t=new Date();
let y=t.getFullYear()-b.getFullYear();
let m=t.getMonth()-b.getMonth();
let d=t.getDate()-b.getDate();
if(d<0){m--;d+=new Date(t.getFullYear(),t.getMonth(),0).getDate()}
if(m<0){y--;m+=12}
result.style.display="flex";
animate("y",y);animate("m",m);animate("d",d);
soundResult();
confetti();
}

function toggleTheme(){document.body.classList.toggle("dark")}
function changeLang(){
lang=(lang+1)%L.length;
title.innerText=L[lang].t;
lbl.innerText=L[lang].l;
btn.innerText=L[lang].b;
yt.innerText=L[lang].y;
mt.innerText=L[lang].m;
dt.innerText=L[lang].d;
document.body.dir=L[lang].dir;
result.style.display="none";
}
</script>

</body>
</html>
