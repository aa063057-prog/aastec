<!DOCTYPE html>
<html lang="pt-BR">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AAS TECNOLOGIA</title>

<link rel="stylesheet" href="css/style.css">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<script src="https://kit.fontawesome.com/4c9e8f4d5d.js" crossorigin="anonymous"></script>
</head>

<body>

<div id="particles"></div>

<header>

<img src="imagens/logo.png" class="logo">

<nav>

<a href="index.html">Início</a>

<a href="filmes.html">Filmes</a>

<a href="series.html">Séries</a>

<a href="faq.html">FAQ</a>

<a href="contato.html">Contato</a>

</nav>

</header>

<section class="banner">

<div class="banner-texto">

<h1>AAS TECNOLOGIA</h1>

<p>
Filmes, séries, esportes e canais em um só lugar.
</p>

<a class="btn" href="contato.html">
ASSINAR AGORA
</a>

</div>

</section>

<section class="contador">

<div>

<h2 id="clientes">0</h2>

<p>Clientes Satisfeitos</p>

</div>

<div>

<h2>+20.000</h2>

<p>Filmes</p>

</div>

<div>

<h2>+8.000</h2>

<p>Séries</p>

</div>

</section>

<section class="compatibilidade">

<h2>Compatível com</h2>

<div class="grid">

<div class="card">📺 TV Box</div>

<div class="card">🔥 Fire Stick</div>

<div class="card">📡 Chromecast</div>

<div class="card">📺 Smart TV Samsung (2020+)</div>

<div class="card">📺 Smart TV LG (2020+)</div>

<div class="card">📺 Roku TV</div>

<div class="card">🤖 Android TV</div>

</div>

</section>

<section>

<h2>Streaming Compatível</h2>

<div class="logos">

<div class="logoCard">Netflix</div>

<div class="logoCard">Prime Video</div>

<div class="logoCard">Disney+</div>

<div class="logoCard">Max</div>

<div class="logoCard">Globoplay</div>

<div class="logoCard">Apple TV+</div>

<div class="logoCard">Paramount+</div>

<div class="logoCard">Premiere</div>

</div>

</section>

<section>

<h2>Por que escolher a AAS TECNOLOGIA?</h2>

<div class="cards">

<div class="info">
⚡ Alta velocidade
</div>

<div class="info">
🎬 Filmes em HD e 4K
</div>

<div class="info">
📺 Canais ao vivo
</div>

<div class="info">
📱 Funciona em vários dispositivos
</div>

</div>

</section>

<section class="faq">

<h2>Perguntas Frequentes</h2>

<details>
<summary>Como recebo acesso?</summary>
<p>Após o pagamento enviamos imediatamente.</p>
</details>

<details>
<summary>Posso testar?</summary>
<p>Consulte disponibilidade.</p>
</details>

<details>
<summary>Funciona na TV?</summary>
<p>Sim, em TV Box, Fire Stick, Chromecast, Roku, Android TV e Smart TVs compatíveis.</p>
</details>

</section>

<a class="whatsapp" href="#">
WhatsApp
</a>

<footer>

© 2026 AAS TECNOLOGIA

</footer>

<script src="js/script.js"></script>

</body>

</html>
/* ===== AAS TECNOLOGIA ===== */

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#090909;
color:#fff;
overflow-x:hidden;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:18px 8%;
background:rgba(0,0,0,.75);
backdrop-filter:blur(10px);
z-index:999;
}

.logo{
height:60px;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:25px;
font-weight:600;
transition:.35s;
}

nav a:hover{
color:#00d9ff;
text-shadow:0 0 15px #00d9ff;
}

.banner{
height:100vh;
background:linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.8)),
url("../imagens/banner.jpg") center/cover;
display:flex;
align-items:center;
padding:8%;
animation:zoom 18s infinite alternate;
}

@keyframes zoom{
0%{
background-size:100%;
}
100%{
background-size:110%;
}
}

.banner h1{
font-size:60px;
margin-bottom:15px;
}

.banner p{
font-size:22px;
max-width:650px;
margin-bottom:35px;
}

.btn{
display:inline-block;
padding:16px 42px;
border-radius:40px;
background:#00d9ff;
color:#000;
font-weight:bold;
text-decoration:none;
transition:.4s;
box-shadow:0 0 20px #00d9ff;
}

.btn:hover{
transform:scale(1.08);
box-shadow:0 0 40px #00d9ff;
}

section{
padding:90px 8%;
animation:fade 1s;
}

@keyframes fade{
from{
opacity:0;
transform:translateY(40px);
}
to{
opacity:1;
transform:translateY(0);
}
}

.contador{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
text-align:center;
}

.contador div{
background:#111;
padding:35px;
border-radius:18px;
transition:.4s;
}

.contador div:hover{
transform:translateY(-10px);
box-shadow:0 0 25px #00d9ff;
}

.contador h2{
font-size:40px;
color:#00d9ff;
}

.compatibilidade h2{
text-align:center;
margin-bottom:45px;
font-size:35px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.card{
background:#121212;
padding:30px;
border-radius:18px;
text-align:center;
font-size:20px;
transition:.4s;
cursor:pointer;
}

.card:hover{
transform:translateY(-12px) scale(1.05);
box-shadow:0 0 25px #00d9ff;
}

.logos{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
}

.logoCard{
background:#181818;
padding:30px;
border-radius:15px;
text-align:center;
font-size:22px;
font-weight:bold;
transition:.4s;
}

.logoCard:hover{
background:#00d9ff;
color:#000;
transform:scale(1.05);
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.info{
background:#101010;
padding:30px;
border-radius:18px;
text-align:center;
font-size:20px;
transition:.4s;
}

.info:hover{
transform:rotateX(8deg) translateY(-8px);
box-shadow:0 0 30px #00d9ff;
}
/* ===== FAQ ===== */

.faq{
max-width:900px;
margin:auto;
}

.faq h2{
text-align:center;
margin-bottom:35px;
font-size:36px;
}

details{
background:#111;
margin:15px 0;
padding:18px;
border-radius:12px;
cursor:pointer;
transition:.4s;
border:1px solid #222;
}

details:hover{
box-shadow:0 0 20px #00d9ff;
transform:translateY(-3px);
}

summary{
font-size:20px;
font-weight:bold;
list-style:none;
}

summary::-webkit-details-marker{
display:none;
}

details p{
margin-top:15px;
line-height:1.6;
color:#d8d8d8;
}

/* ===== Botão WhatsApp ===== */

.whatsapp{
position:fixed;
right:25px;
bottom:25px;
background:#25D366;
color:#fff;
text-decoration:none;
padding:16px 24px;
border-radius:40px;
font-weight:bold;
box-shadow:0 0 20px rgba(37,211,102,.6);
transition:.35s;
z-index:999;
}

.whatsapp:hover{
transform:scale(1.1);
box-shadow:0 0 35px #25D366;
}

/* ===== Rodapé ===== */

footer{
background:#050505;
padding:30px;
text-align:center;
color:#999;
border-top:1px solid #222;
}

/* ===== Fundo animado ===== */

#particles{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
pointer-events:none;
z-index:-1;
background:
radial-gradient(circle at 20% 20%, rgba(0,217,255,.10), transparent 25%),
radial-gradient(circle at 80% 40%, rgba(0,217,255,.08), transparent 30%),
radial-gradient(circle at 50% 90%, rgba(0,217,255,.10), transparent 25%);
animation:fundo 12s ease-in-out infinite alternate;
}

@keyframes fundo{

0%{
transform:translateY(0);
}

100%{
transform:translateY(-30px);
}

}

/* ===== Barra de rolagem ===== */

::-webkit-scrollbar{
width:10px;
}

::-webkit-scrollbar-track{
background:#111;
}

::-webkit-scrollbar-thumb{
background:#00d9ff;
border-radius:20px;
}

::-webkit-scrollbar-thumb:hover{
background:#00ffff;
}

/* ===== Responsivo ===== */

@media(max-width:900px){

header{
flex-direction:column;
padding:15px;
}

nav{
margin-top:15px;
}

nav a{
display:inline-block;
margin:8px;
}

.banner{
text-align:center;
justify-content:center;
}

.banner h1{
font-size:42px;
}

.banner p{
font-size:18px;
}

.btn{
padding:14px 32px;
}

.logo{
height:50px;
}

}

/* ===== Animação ao passar o mouse ===== */

.card,
.logoCard,
.info,
.contador div{
transition:.4s ease;
}

.card:hover,
.logoCard:hover,
.info:hover,
.contador div:hover{
transform:translateY(-10px);
}

/* ===== Títulos ===== */

h2{
color:#ffffff;
margin-bottom:20px;
text-shadow:0 0 10px rgba(0,217,255,.5);
}
// ==============================
// AAS TECNOLOGIA
// Script Principal
// ==============================

// Contador animado
const contador = document.getElementById("clientes");

let valor = 0;
const final = 3500;

const intervalo = setInterval(() => {

    valor += 25;

    contador.innerHTML = valor + "+";

    if(valor >= final){
        contador.innerHTML = "3500+";
        clearInterval(intervalo);
    }

},20);


// Fade ao aparecer
const observer = new IntersectionObserver((entradas)=>{

    entradas.forEach((entrada)=>{

        if(entrada.isIntersecting){

            entrada.target.style.opacity="1";
            entrada.target.style.transform="translateY(0px)";

        }

    });

});

document.querySelectorAll("section").forEach(sec=>{

    sec.style.opacity="0";
    sec.style.transform="translateY(60px)";
    sec.style.transition="1s";

    observer.observe(sec);

});


// Efeito de brilho nos cards
document.querySelectorAll(".card,.logoCard,.info").forEach(card=>{

    card.addEventListener("mousemove",()=>{

        card.style.boxShadow="0 0 35px #00d9ff";

    });

    card.addEventListener("mouseleave",()=>{

        card.style.boxShadow="";

    });

});


// Botão voltar ao topo
const voltar=document.createElement("button");

voltar.innerHTML="⬆";

voltar.style.position="fixed";
voltar.style.bottom="90px";
voltar.style.right="25px";
voltar.style.width="50px";
voltar.style.height="50px";
voltar.style.borderRadius="50%";
voltar.style.border="none";
voltar.style.background="#00d9ff";
voltar.style.cursor="pointer";
voltar.style.fontSize="22px";
voltar.style.display="none";
voltar.style.zIndex="999";

document.body.appendChild(voltar);

window.addEventListener("scroll",()=>{

    if(window.scrollY>400){

        voltar.style.display="block";

    }else{

        voltar.style.display="none";

    }

});

voltar.onclick=()=>{

    window.scrollTo({

        top:0,
        behavior:"smooth"

    });

};


// Efeito nos botões
document.querySelectorAll(".btn").forEach(btn=>{

    btn.addEventListener("mouseenter",()=>{

        btn.style.boxShadow="0 0 40px cyan";

    });

    btn.addEventListener("mouseleave",()=>{

        btn.style.boxShadow="0 0 20px #00d9ff";

    });

});

console.log("AAS TECNOLOGIA carregado com sucesso.");




