<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>guzzdreams</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #f9f9f9;
      color: #222;
    }
    header {
      background-color: #111;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 1.8rem;
      font-weight: bold;
    }
    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background-color: #eee;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    .categories {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin: 2rem 0;
      flex-wrap: wrap;
    }
    .category {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1rem 2rem;
      cursor: pointer;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .socials a {
      color: white;
      margin: 0 0.5rem;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">guzzdreams</div>
    <nav>
      <a href="#remeras">Remeras</a>
      <a href="#pantalones">Pantalones</a>
      <a href="#vestidos">Vestidos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>
  <section class="hero">
    <h1>Elegancia que inspira</h1>
    <p>Descubrí nuestras prendas exclusivas.</p>
  </section>
  <section class="categories">
    <div class="category">Remeras</div>
    <div class="category">Pantalones</div>
    <div class="category">Vestidos</div>
  </section>
  <section class="gallery" id="remeras">
    <!-- Acá van las fotos de remeras -->
    <img src="remera1.jpg" alt="Remera 1">
    <img src="remera2.jpg" alt="Remera 2">
  </section>
  <section class="gallery" id="pantalones">
    <!-- Fotos de pantalones -->
    <img src="pantalon1.jpg" alt="Pantalón 1">
    <img src="pantalon2.jpg" alt="Pantalón 2">
  </section>
  <section class="gallery" id="vestidos">
    <!-- Fotos de vestidos -->
    <img src="vestido1.jpg" alt="Vestido 1">
    <img src="vestido2.jpg" alt="Vestido 2">
  </section>
  <footer id="contacto">
    <p>Seguinos en redes:</p>
    <div class="socials">
      <a href="https://www.instagram.com/guzzdreams" target="_blank">Instagram</a>
      <a href="https://www.facebook.com/guzzdreams" target="_blank">Facebook</a>
      <a href="https://wa.me/1234567890" target="_blank">WhatsApp</a>
    </div>
    <p>&copy; 2025 guzzdreams. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
