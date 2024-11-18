<!DOCTYPE html>
<html lang="es">
<head>
    <head>
        <title>Flower Girl</title>
        <link rel="icon" href="0.jpg" type="image/x-icon">
      </head>  
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: hsla(60, 25%, 2%, 0.895);
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: hsla(60, 2%, 8%, 0.895);
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #ddd;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
            justify-content: center;
        }
        .product {
            width: 200px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            overflow: hidden;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
        }
        .product h3 {
            font-size: 1.1em;
            margin: 10px 0;
        }
        .price {
            color: #e67e22;
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .privacy-policy, .contact, .location {
            display: none;
            padding: 20px;
            background-color: #fff;
            max-width: 600px;
            margin: 20px auto;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
    <script>
        function showSection(sectionId) {
            // Ocultar todas las secciones
            document.querySelectorAll('.privacy-policy, .contact, .location').forEach(section => {
                section.style.display = 'none';
            });
            // Mostrar la sección seleccionada
            document.getElementById(sectionId).style.display = 'block';
            window.scrollTo(0, document.body.scrollHeight);
        }
    </script>
</head>
<body>

<header>
    <h1>Ｆｌｏｗｅｒ Ｇｉｒｌ</h1>
</header>

<nav>
    <a href="#" onclick="showSection('location')">Ubicación</a>
    <a href="#" onclick="showSection('contact')">Contacto</a>
    <a href="#" onclick="showSection('privacy-policy')">Ajustes</a>
</nav>

</div>

<!-- Sección de Ubicación -->
<div id="location" class="location">
    <h2>Ubicación</h2>
    <p>Estamos ubicados en el centro comercial XYZ, Av. Principal 123, Ciudad, País.</p>
</div>

<!-- Sección de Contacto -->
<div id="contact" class="contact">
    <h2>Contacto</h2>
    <p>Teléfono: +52 123 456 7890</p>
    <p>Email: flowergirl@tiendaderopa.com</p>
</div>

<!-- Sección de Políticas de Privacidad -->
<div id="privacy-policy" class="privacy-policy">
    <h2>Políticas</h2>
    <p>Aquí puedes incluir las políticas de privacidad de la tienda...</p>
    <h2>Valores</h2>
    <p>Aquí puedes incluir las políticas de privacidad de la tienda...</p>
    <h2>dh</h2>
    <p>Aquí puedes incluir las políticas de privacidad de la tienda...</p>
</div>

<div class="container">
    <!-- Producto 1 -->
    <div class="product">
        <img src="1.jpg" alt="Suéter Burdeos">
        <h3>Blusa floreada</h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$100.64 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="2.jpg" alt="Jersey estilo vintage">
        <h3>Blusa corta con estampado de hojas </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$100.90 MXN</p>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="3.jpg" alt="Suéter Rosa Botones">
        <h3>Blusa corta sin mangas con estampado de flores </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$83.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="4.jpg" alt="Jersey estilo vintage">
        <h3>Blusa de botones sin manga con short, estilo deslavado</h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$200.90 MXN</p>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="5.jpg" alt="Suéter Rosa Botones">
        <h3>Vestido corto de botones, estilo deslavado </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$180.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="6.jpg" alt="Jersey estilo vintage">
        <h3>Pantalones con diseño astrologico </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="8.jpg" alt="Suéter Rosa Botones">
        <h3>Suéter cafe de vinil </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$283.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="7.jpg" alt="Jersey estilo vintage">
        <h3>Pantalón azul/blanco con diseño de flores blancas</h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="9.jpg" alt="Suéter Rosa Botones">
        <h3>Suéter Rosa </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$283.50 MXN 🛒</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="10.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 3 -->
    <div class="product">
        <img src="11.jpg" alt="Suéter Rosa Botones">
        <h3>Suéter Rosa </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$283.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="12.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

     <!-- Producto 3 -->
     <div class="product">
        <img src="14.jpg" alt="Suéter Rosa Botones">
        <h3>Suéter Rosa </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$283.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="13.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

     <!-- Producto 3 -->
     <div class="product">
        <img src="15.jpg" alt="Suéter Rosa Botones">
        <h3>Suéter Rosa </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$283.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="16.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

     <!-- Producto 3 -->
     <div class="product">
        <img src="17.jpg" alt="Suéter Rosa Botones">
        <h3>Suéter Rosa </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$283.50 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="18.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="19.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="20.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="21.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="22.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="23.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="24.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="25.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>

    <!-- Producto 2 -->
    <div class="product">
        <img src="26.jpg" alt="Jersey estilo vintage">
        <h3>Jersey </h3>
        <h3>Tallas (XXS) (S) (M) (L) (XL) (0XL) (1XL)</h3>
        <p class="price">$256.90 MXN</p>
    </div>
</div>

<!-- Sección de Ubicación -->
<div id="location" class="location">
    <h2>Ubicación</h2>
    <p>Estamos ubicados en el centro comercial XYZ, Av. Principal 123, Ciudad, País.</p>
</div>

<!-- Sección de Contacto -->
<div id="contact" class="contact">
    <h2>Contacto</h2>
    <p>Teléfono: +52 123 456 7890</p>
    <p>Email: flowergirl@tiendaderopa.com</p>
</div>

<!-- Sección de Políticas -->
<div id="policy" class="policy">
    <h2>Políticas</h2>
    <p>Aquí puedes incluir las políticas de privacidad de la tienda...</p>
    <h2></h2>
    <p>Aquí puedes incluir las políticas de privacidad de la tienda...</p>
</div>

</body>
</html>
