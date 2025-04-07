<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guzzdreams</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #fdfdfd;
      color: #333;
    }
    header {
      background-color: black;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #f4f4f4;
      padding: 1rem;
      flex-wrap: wrap;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: black;
      font-weight: bold;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }
    .item {
      border: 1px solid #ddd;
      border-radius: 10px;
      overflow: hidden;
      background: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .item img {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }
    .item h3 {
      margin: 0;
      padding: 1rem;
      text-align: center;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    footer a {
      color: #f8d10f;
      margin: 0 0.5rem;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenidos a Guzzdreams</h1>
    <p>Moda urbana, elegante y única</p>
  </header>  <nav>
    <a href="#jeans">Jeans</a>
    <a href="#remeras">Remeras</a>
    <a href="#buzos">Buzos</a>
    <a href="#camperas">Camperas</a>
    <a href="#pantalones">Pantalones</a>
    <a href="#accesorios">Accesorios</a>
  </nav>  <section id="jeans" class="grid">
    <div class="item">
      <img src="https://via.placeholder.com/300x400?text=Jeans+1" alt="Jeans 1">
      <h3>Jeans 1</h3>
    </div>
    <!-- Más imágenes similares -->
  </section>  <!-- Agregar más secciones igual que la de jeans -->  <footer>
    <p>Seguinos en nuestras redes</p>
    <a href="https://www.instagram.com/guzzdreams" target="_blank">Instagram</a>
    <a href="https://wa.me/541132113760" target="_blank">WhatsApp</a>
    <p>&copy; 2025 Guzzdreams</p>
  </footer>
</body>
</html>
