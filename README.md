<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Guzzdreams</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      background: #fff;
      color: #111;
    }

    header {
      background: #000;
      color: #fff;
      padding: 1em;
      display: flex;
      justify-content: space-between;
      align-items: center; }

    header h1 {
      font-size: 1.5em;
      margin: 0;
    }

    .menu-btn {
      font-size: 1.5em;
      background: none;
      border: none;
      color: white;
      cursor: pointer;
    }

    nav {
      display: none;
      background: #222;
      padding: 1em;
    }

    nav a {
      display: block;
      color: white;
      text-decoration: none;
      margin: 0.5em 0;
    }

    nav.show {
      display: block;
    }

    h2 {
      text-align: center;
      margin-top: 1.5em;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1em;
      padding: 1em;
    }

    .gallery img {
      width: 150px;
      border-radius: 10px;
    }

    footer {
      background: #000;
      color: #fff;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }

    footer a {
      color: #fff;
      text-decoration: none;
      margin: 0 0.5em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Guzzdreams</h1>
    <button class="menu-btn" onclick="toggleMenu()">☰</button>
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

  <section id="jeans">
    <h2>Jeans</h2>
    <div class="gallery">
      <img src="fotos/jean1.jpg" alt="Jean 1" />
      <img src="fotos/jean2.jpg" alt="Jean 2" />
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
    <p style="text-align: center;">Seguinos:</p>
    <p style="text-align: center;">
      <a href="https://wa.me/541132113760">WhatsApp</a> |
      <a href="#">Instagram</a> |
      <a href="#">Facebook</a>
    </p>
  </section>

  <footer>
    <p>© 2025 Guzzdreams</p>
  </footer>

  <script>
    function toggleMenu() {
      document.getElementById("menu").classList.toggle("show");
    }
  </script>

</body>
</html>
