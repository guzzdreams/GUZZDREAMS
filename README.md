<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Guzzdreams</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Montserrat:wght@300;500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #0d0d0d;
      color: #f4f4f4;
    }
    header {
      text-align: center;
      padding: 4rem 2rem;
      background: linear-gradient(to right, #1c1c1c, #000);
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin: 0;
      color: #e6c06b;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 1rem;
      color: #ccc;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #1a1a1a;
      padding: 1rem;
      gap: 2rem;
    }
    nav a {
      color: #e6c06b;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: white;
    }
    section {
      padding: 3rem 2rem;
      text-align: center;
    }
    h2 {
      font-family: 'Playfair Display', serif;
      color: #e6c06b;
    }
    .gallery {
      margin-top: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .item {
      background-color: #1a1a1a;
      padding: 1rem;
      border-radius: 12px;
      transition: transform 0.5s ease;
    }
    .item:hover {
      transform: scale(1.03);
    }
    .item img {
      width: 100%;
      border-radius: 10px;
    }
    .item .info {
      margin-top: 0.8rem;
      color: #ccc;
      font-size: 0.9rem;
    }
    footer {
      background-color: #111;
      text-align: center;
      padding: 2rem 1rem;
      color: #777;
    }
    .socials a {
      margin: 0 1rem;
      color: #e6c06b;
      text-decoration: none;
      font-weight: bold;
    }
    .socials a:hover {
      color: white;
    }
    .whatsapp-button {
      display: inline-block;
      margin-top: 2rem;
      background-color: #25D366;
      color: white;
      padding: 0.8rem 1.5rem;
      border-radius: 30px;
      font-weight: bold;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }
    .whatsapp-button:hover {
      background-color: #1ebe5d;
    }
  </style>
</head>
<body>
  <header>
    <h1>Guzzdreams</h1>
    <p>Ropa con presencia. Elegancia callejera.</p>
  </header>  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#urbano">Urbano</a>
    <a href="#casual">Casual</a>
    <a href="#accesorios">Accesorios</a>
    <a href="#contacto">Contacto</a>
  </nav>  <section id="sobre">
    <h2>Sobre Guzzdreams</h2>
    <p>Guzzdreams es más que ropa. Es una visión. Es presencia, fuerza y estilo. Cada prenda está pensada para transmitir una energía única que acompañe tu esencia en la calle, en la vida y en tus sueños.</p>
  </section>  <section id="urbano">
    <h2>Estilo Urbano</h2>
    <div class="gallery">
      <div class="item">
        <img src="https://source.unsplash.com/400x500/?streetwear" alt="urbano1">
        <div class="info">Hoodie Street - $12.000 - Talles S/M/L</div>
      </div>
      <div class="item">
        <img src="https://source.unsplash.com/401x500/?urban,fashion" alt="urbano2">
        <div class="info">Campera Oversize - $18.500 - Talles M/L/XL</div>
      </div>
      <div class="item">
        <img src="https://source.unsplash.com/402x500/?hoodie,model" alt="urbano3">
        <div class="info">Buzo Crudo - $14.200 - Talles S a XL</div>
      </div>
    </div>
  </section>  <section id="casual">
    <h2>Casual</h2>
    <div class="gallery">
      <div class="item">
        <img src="https://source.unsplash.com/403x500/?casual,clothing" alt="casual1">
        <div class="info">Remera Básica - $7.800 - Talles S/M/L</div>
      </div>
      <div class="item">
        <img src="https://source.unsplash.com/404x500/?jeans,shirt" alt="casual2">
        <div class="info">Camisa Denim - $15.300 - Talles M a XXL</div>
      </div>
      <div class="item">
        <img src="https://source.unsplash.com/405x500/?daily,outfit" alt="casual3">
        <div class="info">Set Día a Día - $20.000 - Talles únicos</div>
      </div>
    </div>
  </section>  <section id="accesorios">
    <h2>Accesorios</h2>
    <div class="gallery">
      <div class="item">
        <img src="https://source.unsplash.com/406x500/?accessories" alt="acc1">
        <div class="info">Gorra Negra - $5.000</div>
      </div>
      <div class="item">
        <img src="https://source.unsplash.com/407x500/?cap,style" alt="acc2">
        <div class="info">Gorra Estilo - $5.500</div>
      </div>
      <div class="item">
        <img src="https://source.unsplash.com/408x500/?fashion,bag" alt="acc3">
        <div class="info">Riñonera Urban - $8.900</div>
      </div>
    </div>
  </section>  <section id="contacto">
    <h2>Contacto</h2>
    <p>Hablá con nosotrxs o seguinos en redes:</p>
    <div class="socials">
      <a href="https://wa.me/5491132113760" target="_blank">WhatsApp</a>
      <a href="https://www.instagram.com/guzzdreams" target="_blank">Instagram</a>
      <a href="https://www.facebook.com/guzzdreams" target="_blank">Facebook</a>
      <a href="mailto:guzzdreams@gmail.com">Email</a>
    </div>
    <a class="whatsapp-button" href="https://wa.me/5491132113760" target="_blank">Comprar por WhatsApp</a>
  </section>  <footer>
    <p>© 2025 Guzzdreams. Todos los derechos reservados.</p>
  </footer>
</body>
</html>