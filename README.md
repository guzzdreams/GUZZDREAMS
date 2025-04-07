<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Guzzdreams</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Montserrat&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #f4f4f4;
      color: #222;
    }

    header {
      background-color: #000;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1em 1.5em;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2em;
      margin: 0;
    }

    .menu-toggle {
      font-size: 2em;
      background: none;
      border: none;
      color: white;
      cursor: pointer;
    }

    nav {
      display: none;
      flex-direction: column;
      background-color: #111;
      padding: 1em;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0.5em 0;
      font-size: 1em;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff69b4;
    }

    nav.show {
      display: flex;
    }

    main {
      padding: 2em 1em;
    }

    section {
      margin-bottom: 3em;
    }

    h2 {
      font-family: 'Playfair Display', serif;
      font-size: 1.8em;
      text-align: center;
      margin-bottom: 1em;
      color: #000;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1em;
      padding: 0 1em;
    }

    .gallery img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.03);
    }

    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 2em 1em;
    }

    footer a {
      color: #fff;
      margin: 0 0.5em;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Guzzdreams</h1>
    <button class="menu-toggle" onclick="toggleMenu()">☰</button>
  </header>

  <nav id="menu">
    <a href="#jeans">Jeans</a>
    <a href="#tops">Tops</a>
    <a href="#vestidos">Vestidos</a>
    <a href="#camperas">Camperas</a>
    <a href="#remeras">Remeras</a>
    <a href="#pantalones">Pantalones</a>
    <a href="#accesorios">Accesorios</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <main>
    <section id="jeans">
      <h2>Jeans</h2>
      <div class="gallery">
        <img src="fotos/jean1.jpg" alt="Jean 1">
        <img src="fotos/jean2.jpg" alt="Jean 2">
      </div>
    </section>

    <section id="tops">
      <h2>Tops</h2>
      <div class="gallery"></div>
    </section>

    <section id="vestidos">
      <h2>Vestidos</h2>
      <div class="gallery"></div>
    </section>

    <section id="camperas">
      <h2>Camperas</h2>
      <div class="gallery"></div>
    </section>

    <section id="remeras">
      <h2>Remeras</h2>
      <div class="gallery"></div>
    </section>

    <section id="pantalones">
      <h2>Pantalones</h2>
      <div class="gallery"></div>
    </section>

    <section id="accesorios">
      <h2>Accesorios</h2>
      <div class="gallery"></div>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p style="text-align: center;">Seguinos en redes:</p>
      <p style="text-align: center;">
        <a href="https://wa.me/541132113760" target="_blank">WhatsApp</a> |
        <a href="#">Instagram</a> |
        <a href="#">Facebook</a>
      </p>
    </section>
  </main>

  <footer>
    <p>© 2025 Guzzdreams</p>
  </footer>

  <script>
    function toggleMenu() {
      const menu = document.getElementById("menu");
      menu.classList.toggle("show");
    }
  </script>

</body>
</html>