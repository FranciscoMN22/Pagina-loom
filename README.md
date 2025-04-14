<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lima Loom</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-white text-gray-800 font-sans">
  <!-- Navbar -->
  <header class="bg-black text-white p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">Lima Loom</h1>
    <nav class="space-x-4">
      <a href="#inicio" class="hover:underline">Inicio</a>
      <a href="#categorias" class="hover:underline">Categorias</a>
      <a href="#testimonios" class="hover:underline">Opiniones</a>
      <a href="#contacto" class="hover:underline">Contacto</a>
      <a href="#carrito" class="hover:underline">Carrito</a>
    </nav>
  </header>

  <!-- Inicio -->
  <section id="inicio" class="p-8 bg-gray-100">
    <h2 class="text-3xl font-bold mb-4">Bienvenido a Lima Loom</h2>
    <p class="mb-4">Explora lo mejor en ropa, tecnologia y mucho mas</p>
    <img src="https://via.placeholder.com/1200x300" alt="Promocion" class="w-full rounded-xl">
  </section>

  <!-- Categorias -->
  <section id="categorias" class="p-8">
    <h2 class="text-2xl font-bold mb-6">Categorias</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <div class="bg-gray-100 p-4 rounded-xl shadow">
        <h3 class="font-semibold text-lg mb-2">Ropa</h3>
        <p>Hombre, Mujer, Niños</p>
      </div>
      <div class="bg-gray-100 p-4 rounded-xl shadow">
        <h3 class="font-semibold text-lg mb-2">Tecnologia</h3>
        <p>Celulares, Laptops, Accesorios</p>
      </div>
      <div class="bg-gray-100 p-4 rounded-xl shadow">
        <h3 class="font-semibold text-lg mb-2">Otros</h3>
        <p>Hogar, Belleza, Deportes</p>
      </div>
    </div>
  </section>

  <!-- Opiniones -->
  <section id="testimonios" class="p-8 bg-gray-100">
    <h2 class="text-2xl font-bold mb-6">Opiniones de Clientes</h2>
    <div class="space-y-4">
      <blockquote class="border-l-4 border-blue-500 pl-4">
        "Excelente calidad y envio rapido. ¡Recomendado!" — Carla M.
      </blockquote>
      <blockquote class="border-l-4 border-blue-500 pl-4">
        "Compre una laptop y llego en 2 dias, todo perfecto." — Jorge L.
      </blockquote>
    </div>
  </section>

  <!-- Carrito de compras -->
  <section id="carrito" class="p-8">
    <h2 class="text-2xl font-bold mb-6">Tu Carrito</h2>
    <p class="mb-4">(Funcion simulada) Productos agregados apareceran aqui.</p>
    <button class="bg-black text-white px-4 py-2 rounded">Pagar</button>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="p-8 bg-gray-200">
    <h2 class="text-2xl font-bold mb-6">Contacto</h2>
    <form class="space-y-4">
      <input type="text" placeholder="Nombre" class="w-full p-2 rounded">
      <input type="email" placeholder="Correo" class="w-full p-2 rounded">
      <textarea placeholder="Tu mensaje" class="w-full p-2 rounded"></textarea>
      <button type="submit" class="bg-black text-white px-4 py-2 rounded">Enviar</button>
    </form>
  </section>

  <footer class="bg-black text-white text-center p-4 mt-8">
    &copy; 2025 Lima Loom. Todos los derechos reservados.
  </footer>
</body>

</html>
