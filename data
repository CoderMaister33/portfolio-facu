<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Facundo Alvarez | Creative Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

body{
  font-family:'Inter',sans-serif;
  background:#fff;
  color:#000;
  overflow-x:hidden;
}

/* NAV */
nav{
  position:fixed;
  width:100%;
  display:flex;
  justify-content:space-between;
  padding:20px 10%;
  background:white;
  border-bottom:1px solid #eee;
  z-index:100;
}

nav h1{
  font-family:'Playfair Display';
}

nav a{
  margin-left:20px;
  text-decoration:none;
  color:black;
  position:relative;
}

nav a::after{
  content:"";
  position:absolute;
  width:0;
  height:2px;
  bottom:-3px;
  left:0;
  background:#c40000;
  transition:0.3s;
}

nav a:hover::after{
  width:100%;
}

/* HERO */
.hero{
  height:100vh;
  display:flex;
  align-items:center;
  padding:0 10%;
}

.hero h2{
  font-size:4rem;
  max-width:800px;
  line-height:1.1;
}

.hero span{
  color:#c40000;
}

.hero p{
  margin-top:20px;
  opacity:0.6;
}

/* SECTIONS */
.section{
  padding:120px 10%;
  border-top:1px solid #eee;
}

/* ANIMATION */
.reveal{
  opacity:0;
  transform:translateY(40px);
  transition:1s ease;
}

.reveal.active{
  opacity:1;
  transform:translateY(0);
}

/* CARDS */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:30px;
}

.card{
  border:1px solid #ddd;
  padding:30px;
  transition:0.4s;
}

.card:hover{
  transform:translateY(-10px);
  border-color:#c40000;
}

/* TITLES */
h3{
  font-family:'Playfair Display';
  font-size:2.2rem;
  margin-bottom:20px;
}

/* SKILLS */
.skills span{
  display:inline-block;
  border:1px solid black;
  padding:10px 14px;
  margin:6px;
  transition:0.3s;
}

.skills span:hover{
  background:black;
  color:white;
}

/* CONTACT */
.contact a{
  color:#c40000;
  text-decoration:none;
}

/* FOOTER */
footer{
  text-align:center;
  padding:50px;
  border-top:1px solid #eee;
  font-size:14px;
  opacity:0.6;
}
</style>
</head>

<body>

<nav>
  <h1>Facundo Alvarez</h1>
  <div>
    <a href="#about">About</a>
    <a href="#work">Work</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<section class="hero">
  <div>
    <h2 class="reveal">No hago publicidad.<br><span>Construyo valor para las marcas.</span></h2>
    <p class="reveal">Creativo enfocado en estrategia, cuentas y negocio.</p>
  </div>
</section>

<section id="about" class="section reveal">
  <h3>Sobre mí</h3>
  <p>
    Estudiante de Publicidad en UADE con enfoque en dirección de cuentas.
    Me interesa entender a fondo los negocios para construir estrategias que conecten marcas con personas.
    Busco crecer profesionalmente dentro del mundo publicitario.
  </p>
</section>

<section id="work" class="section">
  <h3 class="reveal">Experiencia & Proyectos</h3>

  <div class="grid">

    <div class="card reveal">
      <h4>Logística Naval</h4>
      <p>Gestión de redes sociales + UX en sitio web.</p>
      <a href="https://www.logisticanaval.com.ar/" target="_blank">Ver proyecto</a>
    </div>

    <div class="card reveal">
      <h4>Festival PIÑA</h4>
      <p>Campaña para Mundial 2026 — YPF + NINCH.</p>
      <a href="https://docs.google.com/presentation/d/1ysfBiXsdlIbIGFqWksBDBcAnGyepsW2wo95g-L3WCiA/edit" target="_blank">Ver caso</a>
    </div>

  </div>
</section>

<section class="section reveal">
  <h3>Herramientas</h3>
  <div class="skills">
    <span>Photoshop</span>
    <span>Premiere</span>
    <span>IA</span>
    <span>Marketing</span>
    <span>Inglés</span>
  </div>
</section>

<section id="contact" class="section reveal">
  <h3>Contacto</h3>
  <p>Email: agusfacu02@gmail.com</p>
  <p>Tel: 1123069902</p>
  <p><a href="https://www.linkedin.com/in/facu-alvarez02/">LinkedIn</a></p>
</section>

<footer>
  <p>© 2026 Facundo Alvarez</p>
</footer>

<script>
function revealOnScroll(){
  let reveals=document.querySelectorAll('.reveal');

  for(let i=0;i<reveals.length;i++){
    let windowHeight=window.innerHeight;
    let elementTop=reveals[i].getBoundingClientRect().top;
    let elementVisible=100;

    if(elementTop < windowHeight - elementVisible){
      reveals[i].classList.add("active");
    }
  }
}

window.addEventListener("scroll",revealOnScroll);
</script>

</body>
</html>
