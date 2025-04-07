<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Guzzdreams</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdfdfd;
      color: #333;
    }
    header {
      background-color: #000;
      color: white;
      padding: 1em;
      text-align: center;
      font-size: 2em;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5em;
      background-color: #f2f2f2;
      padding: 1em;
    }
    nav a {
      text-decoration: none;
      color: #000;
      font-weight: bold;
    }
    .section {
      padding: 2em;
      text-align: center;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1em;
      padding: 1em;
    }
    .item {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1em;
    }
    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 1em;
    }
    .socials a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>Guzzdreams</header>
  <nav>
    <a href="#remeras">Remeras</a>
    <a href="#pantalones">Pantalones</a>
    <a href="#buzos">Buzos</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <div class="section" id="remeras">
    <h2>Remeras</h2>
    <div class="grid">
      <div class="item">Remera 1</div>
      <div class="item">Remera 2</div>
    </div>
  </div>

  <div class="section" id="pantalones">
    <h2>Pantalones</h2>
    <div class="grid">
      <div class="item">Pantalón 1</div>
      <div class="item">Pantalón 2</div>
    </div>
  </div>

  <div class="section" id="buzos">
    <h2>Buzos</h2>
    <div class="grid">
      <div class="item">Buzo 1</div>
      <div class="item">Buzo 2</div>
    </div>
  </div>

  <div class="section" id="contacto">
    <h2>Contacto</h2>
    <p>Seguinos en nuestras redes:</p>
    <p class="socials">
      <a href="https://www.instagram.com/guzzdreams" target="_blank">Instagram</a> |
      <a href="https://wa.me/549xxxxxxxxxx" target="_blank">WhatsApp</a>
    </p>
  </div>

  <footer>
    © 2025 Guzzdreams. Todos los derechos reservados.
  </footer>
</body>
</html>