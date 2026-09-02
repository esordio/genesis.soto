<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Génesis Soto Sepúlveda — Investigación en resistencia antimicrobiana</title>
<meta name="description" content="Génesis Lucía Soto Sepúlveda, Médica Veterinaria y doctoranda en Ciencias Silvoagropecuarias y Veterinarias, Universidad de Chile. Investigación en resistencia antimicrobiana bajo el enfoque One Health.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,500;0,6..72,600;1,6..72,400;1,6..72,500&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --agar: #EAF2F8;
    --ink: #1E2A38;
    --ink-soft: #4C5D70;
    --accent: #4E7FB0;
    --accent-deep: #315D82;
    --accent-soft: #9AC0DC;
    --line: #CBDCEA;
    --paper: #F9FCFE;
    --max: 880px;
  }

  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    margin:0;
    background:var(--agar);
    color:var(--ink);
    font-family:'IBM Plex Sans', sans-serif;
    line-height:1.65;
    font-size:17px;
  }
  h1,h2,h3,.serif{
    font-family:'Newsreader', serif;
    font-weight:500;
    color:var(--ink);
    line-height:1.15;
  }
  em.sp{
    font-style:italic;
  }
  a{color:var(--accent-deep);}
  a:hover{color:var(--accent);}
  a:focus-visible, button:focus-visible{
    outline:2px solid var(--accent-deep);
    outline-offset:3px;
  }

  .wrap{max-width:var(--max); margin:0 auto; padding:0 28px;}

  /* ---------- header ---------- */
  header.top{
    padding:26px 0;
    border-bottom:1px solid var(--line);
  }
  header.top .wrap{display:flex; justify-content:space-between; align-items:center; gap:16px; flex-wrap:wrap;}
  .brand{font-family:'Newsreader', serif; font-size:19px; font-weight:500;}
  nav a{
    margin-left:22px;
    text-decoration:none;
    color:var(--ink-soft);
    font-size:14.5px;
  }
  nav a:first-child{margin-left:0;}
  nav a:hover{color:var(--accent-deep);}

  /* ---------- hero ---------- */
  .hero{padding:70px 0 60px;}
  .hero .wrap{
    display:grid;
    grid-template-columns:1.15fr 0.85fr;
    gap:48px;
    align-items:center;
  }
  .hero-eyebrow{
    font-size:14.5px;
    color:var(--accent-deep);
    margin:0 0 14px;
  }
  .hero h1{
    font-size:44px;
    margin:0 0 14px;
    letter-spacing:-0.01em;
  }
  .hero .role{
    font-size:17px;
    color:var(--ink-soft);
    max-width:46ch;
    margin:0 0 26px;
  }
  .hero .actions{display:flex; gap:14px; flex-wrap:wrap;}
  .btn{
    display:inline-block;
    padding:11px 20px;
    border-radius:3px;
    text-decoration:none;
    font-size:14.5px;
    border:1px solid var(--ink);
  }
  .btn.primary{background:var(--ink); color:var(--paper);}
  .btn.primary:hover{background:var(--accent-deep); border-color:var(--accent-deep); color:var(--paper);}
  .btn.ghost{background:transparent; color:var(--ink); border-color:var(--ink);}
  .btn.ghost:hover{border-color:var(--accent-deep); color:var(--accent-deep);}

  /* ---------- hero media: video + QR ---------- */
  .hero-media{display:flex; flex-direction:column; align-items:center; gap:14px;}
  .hero-video{
    width:100%;
    max-width:230px;
    border-radius:16px;
    overflow:hidden;
    border:1px solid var(--line);
    background:#0B0F14;
  }
  .hero-video video{display:block; width:100%; height:auto;}
  .hero-caption{
    margin:0;
    font-size:13px;
    color:var(--ink-soft);
    text-align:center;
    max-width:230px;
  }
  .hero-qr-chip{
    display:flex;
    align-items:center;
    gap:12px;
    background:var(--paper);
    border:1px solid var(--line);
    border-radius:10px;
    padding:8px 16px 8px 8px;
    text-decoration:none;
  }
  .hero-qr-chip img{
    width:56px;
    height:56px;
    object-fit:contain;
    border-radius:4px;
    flex:none;
  }
  .hero-qr-chip .chip-text{font-size:12.5px; color:var(--ink-soft); line-height:1.4; text-align:left;}
  .hero-qr-chip .chip-text strong{
    display:block;
    color:var(--ink);
    font-family:'Newsreader', serif;
    font-size:15px;
    font-weight:500;
  }
  .hero-qr-chip:hover .chip-text strong{color:var(--accent-deep);}

  /* ---------- sections ---------- */
  section{padding:56px 0;}
  .divider{border:none; border-top:1px solid var(--line); margin:0;}

  .section-head{
    display:flex;
    align-items:baseline;
    gap:14px;
    margin-bottom:26px;
  }
  .section-head .dot{
    width:11px; height:11px; border-radius:50%;
    background:var(--accent);
    flex:none;
    transform:translateY(-2px);
  }
  .section-head h2{font-size:26px; margin:0;}

  .research p{max-width:64ch; color:var(--ink-soft); font-size:16.5px;}
  .research p + p{margin-top:16px;}
  .tagline{
    margin-top:24px;
    padding-left:18px;
    border-left:2px solid var(--accent);
    font-family:'Newsreader', serif;
    font-style:italic;
    font-size:17px;
    color:var(--ink);
    max-width:56ch;
  }

  /* ---------- species ---------- */
  .species-lede{max-width:60ch; color:var(--ink-soft); margin:0 0 32px; font-size:16.5px;}
  .species-grid{
    display:grid;
    grid-template-columns:repeat(3, minmax(0,1fr));
    gap:22px;
  }
  .species-card{
    background:var(--paper);
    border:1px solid var(--line);
    border-radius:4px;
    padding:22px 18px 22px;
    text-align:center;
  }
  .species-card img{
    display:block;
    margin:0 auto 14px;
    height:150px;
    width:auto;
    max-width:100%;
    object-fit:contain;
  }
  .species-card h3{font-size:17px; margin:0 0 6px; font-weight:500;}
  .species-card p{font-size:14px; color:var(--ink-soft); margin:0; max-width:22ch; margin-inline:auto;}

  @media (max-width:600px){
    .species-grid{grid-template-columns:1fr; }
  }

  /* ---------- specimen card (contribution) ---------- */
  .specimen{
    background:var(--paper);
    border:1px solid var(--line);
    border-radius:4px;
    padding:30px 32px;
    position:relative;
  }
  .specimen::before{
    content:"";
    position:absolute;
    top:0; left:28px;
    width:64px; height:8px;
    background:var(--accent-soft);
    opacity:0.7;
    border-radius:0 0 3px 3px;
  }
  .specimen .label-tag{
    font-size:12.5px;
    letter-spacing:0.03em;
    color:var(--accent-deep);
    margin:0 0 10px;
  }
  .specimen h3{
    font-size:21px;
    margin:0 0 14px;
    max-width:38ch;
  }
  .specimen p.desc{color:var(--ink-soft); max-width:62ch; margin:0 0 20px; font-size:16px;}
  .fields{
    display:grid;
    grid-template-columns:repeat(2, minmax(0,1fr));
    gap:14px 28px;
    border-top:1px solid var(--line);
    padding-top:18px;
    font-size:14.5px;
  }
  .fields dt{color:var(--ink-soft); margin:0 0 3px;}
  .fields dd{margin:0; color:var(--ink);}

  /* ---------- contact / qr ---------- */
  .contact-grid{
    display:grid;
    grid-template-columns:1fr auto;
    gap:40px;
    align-items:center;
  }
  .contact-info p{color:var(--ink-soft); max-width:42ch; margin:0 0 18px;}
  .mail-line{
    display:inline-flex;
    align-items:center;
    gap:10px;
    font-family:'Newsreader', serif;
    font-size:19px;
    text-decoration:none;
    color:var(--ink);
    border-bottom:1px solid var(--accent);
    padding-bottom:3px;
  }
  .mail-line:hover{color:var(--accent-deep);}

  .qr-box{
    width:168px;
    height:168px;
    border:1.5px dashed var(--line);
    border-radius:4px;
    display:flex;
    flex-direction:column;
    align-items:center;
    justify-content:center;
    gap:8px;
    text-align:center;
    padding:12px;
  }
  .qr-box img{width:100%; height:100%; object-fit:contain; display:none;}
  .qr-box .qr-placeholder-text{font-size:12px; color:var(--ink-soft); line-height:1.4;}

  /* ---------- footer ---------- */
  footer{
    padding:34px 0 46px;
    border-top:1px solid var(--line);
  }
  footer .wrap{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
    gap:10px;
  }
  footer p{margin:0; font-size:13.5px; color:var(--ink-soft);}
  footer .colonies{display:flex; gap:6px;}
  footer .colonies span{width:7px; height:7px; border-radius:50%; background:var(--accent); opacity:0.7;}
  footer .colonies span:nth-child(2){background:var(--accent-soft);}
  footer .colonies span:nth-child(3){background:var(--accent); opacity:0.4;}

  @media (max-width:760px){
    .hero .wrap{grid-template-columns:1fr; text-align:left;}
    .hero-media{order:-1; margin-bottom:8px; align-items:flex-start;}
    .hero-video{margin-inline:0;}
    .hero h1{font-size:33px;}
    .fields{grid-template-columns:1fr;}
    .contact-grid{grid-template-columns:1fr; justify-items:start;}
    nav a{margin-left:14px;}
  }
</style>
</head>
<body>

<header class="top">
  <div class="wrap">
    <div class="brand">Génesis Soto Sepúlveda</div>
    <nav>
      <a href="#investigacion">Investigación</a>
      <a href="#especies">Especies</a>
      <a href="#contribucion">Contribución</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </div>
</header>

<div class="hero">
  <div class="wrap">
    <div>
      <p class="hero-eyebrow">One Health · Resistencia antimicrobiana</p>
      <h1>Génesis Lucía<br>Soto Sepúlveda</h1>
      <p class="role">Médica Veterinaria · Estudiante de Doctorado en Ciencias Silvoagropecuarias y Veterinarias, Universidad de Chile. Investigo la circulación de <em class="sp">Escherichia coli</em> resistente entre animales de compañía, aves de producción y el ambiente.</p>
      <div class="actions">
        <a class="btn primary" href="#contacto">Escríbeme</a>
        <a class="btn ghost" href="#investigacion">Ver investigación</a>
      </div>
    </div>
    <div class="hero-media">
      <div class="hero-video">
        <video src="assets/siembra.mp4" poster="assets/siembra-poster.jpg" autoplay muted loop playsinline aria-label="Animación de la siembra por agotamiento en cuatro cuadrantes sobre una placa de cultivo"></video>
      </div>
      <p class="hero-caption">Siembra por agotamiento en 4 cuadrantes</p>
      <a class="hero-qr-chip" href="mailto:genesis.soto@ug.uchile.cl" aria-label="Enviar un correo a Génesis Soto">
        <img src="assets/qr.png" alt="Código QR para enviarme un correo">
        <span class="chip-text"><strong>Escríbeme</strong>Escanea o toca el QR</span>
      </a>
    </div>
  </div>
</div>

<hr class="divider">

<section id="investigacion" class="research">
  <div class="wrap">
    <div class="section-head"><span class="dot"></span><h2>Investigación</h2></div>
    <p>Aunque solo el 6% de los tutores de mascotas utiliza dietas crudas exclusivas para sus animales de compañía, más del 50% incorpora carne de pollo o sus derivados como snack o complemento en la alimentación de perros y gatos. Al no recibir tratamiento térmico, esta práctica expone a las mascotas a <em class="sp">Escherichia coli</em> patógena aviar (APEC), cuya relación genética con las cepas de <em class="sp">Escherichia coli</em> uropatógenas (UPEC) circulantes en caninos y felinos aún se desconoce.</p>
    <p>Mi investigación de doctorado busca esclarecer ese vínculo, evaluando el rol de las aves de producción como reservorio de patógenos extraintestinales resistentes a antimicrobianos y su capacidad de generar enfermedad entre especies, en el marco de un enfoque One Health que conecta la salud animal, humana y ambiental.</p>
    <p class="tagline">Actualmente trabajo como asistente de proyectos y coordinadora de tesistas en el laboratorio MicroVet-VacciVet de la Facultad de Ciencias Veterinarias y Pecuarias, Universidad de Chile.</p>
  </div>
</section>

<hr class="divider">

<section id="especies">
  <div class="wrap">
    <div class="section-head"><span class="dot"></span><h2>Especies de estudio</h2></div>
    <p class="species-lede">Mi trabajo sigue la ruta que recorre <em class="sp">Escherichia coli</em> entre distintos huéspedes: aves de producción, perros y gatos, comparando las cepas que circulan en cada uno.</p>
    <div class="species-grid">

      <div class="species-card">
        <img src="assets/chick.png" alt="Pollo broiler" loading="lazy">
        <h3>Aves de producción</h3>
        <p>APEC en pollos broiler</p>
      </div>

      <div class="species-card">
        <img src="assets/puppy.png" alt="Perro cachorro" loading="lazy">
        <h3>Caninos</h3>
        <p>UPEC en perros</p>
      </div>

      <div class="species-card">
        <img src="assets/kitten.png" alt="Gatito" loading="lazy">
        <h3>Felinos</h3>
        <p>UPEC en gatos</p>
      </div>

    </div>
  </div>
</section>

<hr class="divider">

<section id="contribucion">
  <div class="wrap">
    <div class="section-head"><span class="dot"></span><h2>Contribución a la comunidad</h2></div>
    <div class="specimen">
      <p class="label-tag">Memoria de título · 2025</p>
      <h3>Oxitetraciclina en el entorno productivo de pollos broiler: efecto sobre la resistencia antimicrobiana y la formación de biopelículas de <em class="sp">Escherichia coli</em></h3>
      <p class="desc">Este trabajo mostró que el tratamiento con oxitetraciclina en pollos broiler favorece la aparición de <em class="sp">E. coli</em> resistente a tetraciclinas en camas, deyecciones, comederos y bebederos, y que esa resistencia se asocia a una mayor formación de biopelículas. La capacidad de formar biopelículas disminuyó a medida que bajaba la concentración del antimicrobiano en el ambiente, lo que sugiere que estas comunidades bacterianas actúan como un mecanismo de persistencia de la resistencia dentro de la producción avícola y un punto crítico para su diseminación hacia la cadena alimentaria.</p>
      <dl class="fields">
        <div><dt>Financiamiento</dt><dd>Proyecto FONDECYT Regular N.º 1220520</dd></div>
        <div><dt>Profesora guía</dt><dd>Javiera Cornejo Kelly</dd></div>
        <div><dt>Institución</dt><dd>Universidad de Chile, Facultad de Ciencias Veterinarias y Pecuarias</dd></div>
        <div><dt>Palabras clave</dt><dd><em class="sp">Escherichia coli</em>, resistencia antimicrobiana, biopelículas, producción avícola</dd></div>
      </dl>
    </div>
    <p class="tagline">Quiero seguir contribuyendo a la comunidad, aportando las bases que permitan regularizar en el área animal —sobre todo en animales de compañía— la ingesta de antimicrobianos.</p>
  </div>
</section>

<hr class="divider">

<section id="contacto">
  <div class="wrap">
    <div class="section-head"><span class="dot"></span><h2>Contacto</h2></div>
    <div class="contact-grid">
      <div class="contact-info">
        <p>Para consultas académicas, colaboraciones o preguntas sobre mi investigación, escríbeme directamente.</p>
        <a class="mail-line" href="mailto:genesis.soto@ug.uchile.cl">genesis.soto@ug.uchile.cl</a>
      </div>
      <div class="qr-box">
        <img src="assets/qr.png" alt="Código QR de contacto" onload="this.style.display='block'; this.nextElementSibling.style.display='none';" onerror="this.style.display='none';">
        <span class="qr-placeholder-text">Coloca aquí tu código QR<br>(assets/qr.png)</span>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    <p>Génesis Soto Sepúlveda · Santiago, Chile</p>
    <div class="colonies" aria-hidden="true"><span></span><span></span><span></span></div>
  </div>
</footer>

</body>
</html>
