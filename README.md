# Mi-tienda
Productos y Servicios de Alta Calidad

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  Business Friend - Tienda Online
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Business Friend</h1>
    <p>Tu tienda online de ropa exclusiva</p>
  </header>

  <nav>
    <a href="#productos">Productos</a>
    <a href="#carrito">Carrito</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section class="hero">
    <p>Nueva colección disponible ✨</p>
  </section>

  <section id="productos" class="productos">
    <div class="card">
      <img src="https://picsum.photos/300/300?clothes1" alt="Producto 1">
      <h3>Camiseta Estilo Street</h3>
      <p>$25.00</p>
      <button onclick="agregarAlCarrito('Camiseta Estilo Street',25)">Añadir al carrito</button>
    </div>
    <div class="card">
      <img src="https://picsum.photos/300/300?clothes2" alt="Producto 2">
      <h3>Chaqueta Denim</h3>
      <p>$40.00</p>
      <button onclick="agregarAlCarrito('Chaqueta Denim',40)">Añadir al carrito</button>
    </div>
    <div class="card">
      <img src="https://picsum.photos/300/300?clothes3" alt="Producto 3">
      <h3>Pantalón Jogger</h3>
      <p>$30.00</p>
      <button onclick="agregarAlCarrito('Pantalón Jogger',30)">Añadir al carrito</button>
    </div>
  </section>

  <section id="carrito">
    <h2>🛒 Carrito de Compras</h2>
    <ul id="lista-carrito"></ul>
    <p id="total">Total: $0</p>
    <button onclick="finalizarCompra()">Finalizar Compra</button>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>Somos una tienda online dedicada a ofrecer ropa moderna y de calidad. Nuestra misión es que vistas con estilo y comodidad sin pagar de más.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>📧 contacto@businessfriend.com</p>
    <p>📱 WhatsApp: +593 987654321</p>
  </section>

  <footer>
    <p>© 2025 Moda Urbana - Todos los derechos reservados</p>
  </footer>

</body>
</html>

