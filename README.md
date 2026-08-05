# <!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Império Digital</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#090909;
color:#fff;
}

header{
position:fixed;
width:100%;
top:0;
left:0;
padding:18px 8%;
background:rgba(0,0,0,.75);
backdrop-filter:blur(12px);
display:flex;
justify-content:space-between;
align-items:center;
z-index:999;
}

.logo{
font-size:28px;
font-weight:bold;
color:#d4af37;
}

nav a{
color:#fff;
text-decoration:none;
margin-left:25px;
transition:.3s;
}

nav a:hover{
color:#d4af37;
}

.hero{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:120px 20px;
background:
linear-gradient(rgba(0,0,0,.75),rgba(0,0,0,.85)),
url("https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1600&q=80");
background-size:cover;
background-position:center;
}

.hero h1{
font-size:55px;
margin-bottom:20px;
color:#d4af37;
animation:fadeUp 1s;
}

.hero p{
font-size:20px;
max-width:800px;
margin:auto;
margin-bottom:35px;
animation:fadeUp 1.4s;
}

.btn{
display:inline-block;
padding:16px 40px;
background:linear-gradient(45deg,#d4af37,#ffd700);
color:#000;
font-weight:bold;
border-radius:50px;
text-decoration:none;
transition:.35s;
box-shadow:0 0 25px #d4af37;
animation:fadeUp 1.8s;
}

.btn:hover{
transform:translateY(-5px);
box-shadow:0 0 40px gold;
}

section{
padding:90px 8%;
}

h2{
text-align:center;
font-size:38px;
margin-bottom:50px;
color:#d4af37;
}

.about{
max-width:1000px;
margin:auto;
text-align:center;
line-height:1.9;
font-size:18px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;
}

.card{
background:#111;
border:1px solid rgba(212,175,55,.3);
border-radius:15px;
overflow:hidden;
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 25px rgba(212,175,55,.5);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.price{
font-size:25px;
color:#ffd700;
font-weight:bold;
margin:15px 0;
}

.buy{
display:block;
text-align:center;
background:#d4af37;
padding:14px;
color:#000;
text-decoration:none;
font-weight:bold;
border-radius:10px;
transition:.3s;
}

.buy:hover{
background:#ffd700;
box-shadow:0 0 20px gold;
}

.benefits{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.benefit{
background:#111;
padding:30px;
border-radius:15px;
text-align:center;
transition:.3s;
}

.benefit:hover{
transform:translateY(-8px);
}

.benefit i{
font-size:45px;
color:#d4af37;
margin-bottom:15px;
}

.testimonials{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;
}

.testimonial{
background:#111;
padding:25px;
border-radius:15px;
text-align:center;
}

.testimonial img{
width:90px;
height:90px;
border-radius:50%;
margin-bottom:15px;
border:3px solid gold;
}

.faq details{
background:#111;
padding:18px;
margin-bottom:15px;
border-radius:10px;
}

footer{
background:#000;
padding:35px;
text-align:center;
}

footer a{
color:#d4af37;
margin:0 12px;
text-decoration:none;
}

.fade{
opacity:0;
transform:translateY(30px);
transition:1s;
}

.fade.show{
opacity:1;
transform:translateY(0);
}

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(30px);
}
to{
opacity:1;
transform:translateY(0);
}
}

@media(max-width:768px){

.hero h1{
font-size:38px;
}

.hero p{
font-size:17px;
}

nav{
display:none;
}

}
</style>
</head>

<body>

<header>

<div class="logo">
Império Digital
</div>

<nav>
<a href="#sobre">Sobre</a>
<a href="#produtos">Produtos</a>
<a href="#beneficios">Benefícios</a>
<a href="#depoimentos">Depoimentos</a>
<a href="#faq">FAQ</a>
</nav>

</header>

<section class="hero">

<div>

<h1>Império Digital – Transforme Conhecimento em Lucro</h1>

<p>
Aprenda estratégias para ganhar dinheiro na internet,
criar renda extra e desenvolver sua mentalidade financeira.
</p>

<a href="#produtos" class="btn">
Começar Agora
</a>

</div>

</section>

<section id="sobre" class="fade">

<h2>Sobre o Império Digital</h2>

<div class="about">

O <strong>Império Digital</strong> é um projeto criado para ensinar pessoas a construir patrimônio por meio da internet. Você aprenderá Marketing Digital, Vendas Online, Criação de Ativos Digitais, Investimentos, Estratégias de Escala e Desenvolvimento Financeiro com conteúdos práticos voltados tanto para iniciantes quanto para quem deseja alcançar um novo nível de resultados.

</div>

</section>

<section id="produtos" class="fade">

<h2>Produtos</h2>

<div class="grid">

<div class="card">

<img src="https://images.unsplash.com/photo-1516321497487-e288fb19713f?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<h3>E-book Marketing Digital</h3>

<p>Aprenda do zero como vender todos os dias pela internet.</p>

<div class="price">R$ 49,90</div>

<a href="#" class="buy">
Comprar Agora
</a>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<h3>Curso Completo</h3>

<p>Marketing Digital, Funis, Tráfego Pago e Estratégias Avançadas.</p>

<div class="price">R$ 197,00</div>

<a href="#" class="buy">
Comprar Agora
</a>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1552664730-d307ca884978?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<h3>Mentoria Premium</h3>

<p>Acompanhamento exclusivo para acelerar seus resultados.</p>

<div class="price">R$ 997,00</div>

<a href="#" class="buy">
Comprar Agora
</a>

</div>

</div>

</div>

</section>

<section id="beneficios" class="fade">

<h2>Benefícios</h2>

<div class="benefits">

<div class="benefit">
<i class="fa-solid fa-bolt"></i>
<h3>Acesso Imediato</h3>
</div>

<div class="benefit">
<i class="fa-solid fa-rotate"></i>
<h3>Conteúdo Atualizado</h3>
</div>

<div class="benefit">
<i class="fa-solid fa-headset"></i>
<h3>Suporte ao Cliente</h3>
</div>

<div class="benefit">
<i class="fa-solid fa-chart-line"></i>
<h3>Estratégias Práticas</h3>
</div>

<div class="benefit">
<i class="fa-solid fa-graduation-cap"></i>
<h3>Do Básico ao Avançado</h3>
</div>

</div>

</section>

<section id="depoimentos" class="fade">

<h2>Depoimentos</h2>

<div class="testimonials">

<div class="testimonial">

<img src="https://randomuser.me/api/portraits/men/32.jpg">

<h3>Carlos Silva</h3>

<p>
"Consegui fazer minhas primeiras vendas em poucas semanas. Conteúdo excelente."
</p>

</div>

<div class="testimonial">

<img src="https://randomuser.me/api/portraits/women/44.jpg">

<h3>Juliana Souza</h3>

<p>
"Material muito bem explicado. Valeu cada centavo investido."
</p>

</div>

<div class="testimonial">

<img src="https://randomuser.me/api/portraits/men/54.jpg">

<h3>Marcos Lima</h3>

<p>
"A mentoria mudou minha forma de enxergar os negócios digitais."
</p>

</div>

</div>

</section>

<section id="faq" class="fade">

<h2>Perguntas Frequentes</h2>

<details>
<summary>Como recebo o acesso?</summary>
<p>O acesso é enviado automaticamente após a confirmação do pagamento.</p>
</details>

<details>
<summary>Posso assistir pelo celular?</summary>
<p>Sim. Todo o conteúdo é responsivo e funciona em qualquer dispositivo.</p>
</details>

<details>
<summary>Há suporte?</summary>
<p>Sim. Nossa equipe está pronta para tirar dúvidas.</p>
</details>

</section>

<footer>

<p>© 2026 Império Digital - Todos os direitos reservados.</p>

<br>

<a href="#">Instagram</a>

<a href="#">WhatsApp</a>

<a href="#">Política de Privacidade</a>

<a href="#">Termos de Uso</a>

<a href="#">Contato</a>

</footer>

<script>

const itens=document.querySelectorAll(".fade");

window.addEventListener("scroll",()=>{

itens.forEach(item=>{

const pos=item.getBoundingClientRect().top;

if(pos<window.innerHeight-100){

item.classList.add("show");

}

});

});

</script>

</body>
</html>