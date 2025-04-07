<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda de Recomendaciones</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      transition: all 0.3s ease-in-out;
    }
    header {
      background-color: #232f3e;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #37475a;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ff9900;
    }
    .buscador {
      text-align: center;
      padding: 20px;
    }
    .buscador input {
      padding: 10px;
      width: 90%;
      max-width: 500px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .producto {
      background-color: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.2s;
    }
    .producto:hover {
      transform: translateY(-5px);
    }
    .producto img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .producto h3 {
      font-size: 18px;
      margin: 10px 0;
    }
    .producto a {
      background-color: #ff9900;
      color: white;
      padding: 10px 15px;
      border: none;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      display: inline-block;
      margin-top: 10px;
      transition: background-color 0.3s;
    }
    .producto a:hover {
      background-color: #cc7a00;
    }
    footer {
      background-color: #232f3e;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Tienda de Recomendaciones</h1>
    <p>Descubrí los productos más vendidos y ganá comisiones con Amazon Afiliados</p>
  </header>  <nav>
    <a href="#">Inicio</a>
    <a href="#">Tecnología</a>
    <a href="#">Hogar</a>
    <a href="#">Fitness</a>
    <a href="#">Moda</a>
    <a href="#">Contacto</a>
  </nav>  <section class="buscador">
    <input type="text" placeholder="Buscar productos...">
  </section>  <section class="productos">
    <div class="producto">
      <img src="https://via.placeholder.com/250x250" alt="Producto 1">
      <h3>Nombre del Producto 1</h3>
      <p>Descripción corta del producto para motivar la compra.</p>
      <a href="#" target="_blank">Ver en Amazon</a>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/250x250" alt="Producto 2">
      <h3>Nombre del Producto 2</h3>
      <p>Descripción corta del producto para motivar la compra.</p>
      <a href="#" target="_blank">Ver en Amazon</a>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/250x250" alt="Producto 3">
      <h3>Nombre del Producto 3</h3>
      <p>Descripción corta del producto para motivar la compra.</p>
      <a href="#" target="_blank">Ver en Amazon</a>
    </div>
  </section>  <footer>
    <p>&copy; 2025 Tienda de Recomendaciones. Participante del Programa de Afiliados de Amazon.</p>
  </footer>
</body>
</html>
