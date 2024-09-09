<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> CALAFISH </title>
    <style>
        /* Estilos básicos */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background: url('https://www.w3schools.com/w3images/ocean.jpg') no-repeat center center fixed;
            background-size: cover;
        }

        header {
            background: rgba(0, 0, 128, 0.7); /* Color de fondo azul marino semi-transparente */
            color: #fff;
            padding: 1rem;
            text-align: center;
            border-bottom: 5px solid #00bfff; /* Borde inferior azul claro */
        }

        header h1 {
            font-family: 'Arial', sans-serif;
            font-size: 2.5rem;
            margin: 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 1rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2rem;
        }

        nav ul li a:hover {
            color: #00bfff;
        }

        section {
            padding: 2rem;
            margin: 1rem 0;
            text-align: center;
            background: rgba(255, 255, 255, 0.8); /* Fondo blanco semi-transparente para mejor legibilidad */
            border-radius: 10px;
        }

        footer {
            background: rgba(0, 0, 128, 0.7); /* Color de fondo azul marino semi-transparente */
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
            border-top: 5px solid #00bfff; /* Borde superior azul claro */
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-top: 1rem;
        }

        .social-media {
            margin-top: 1rem;
        }

        .social-media a {
            margin: 0 0.5rem;
            text-decoration: none;
            color: #fff;
            font-size: 1.5rem;
        }

        .social-media a:hover {
            color: #00bfff;
        }

        .product-description, .vision-mission, .about-extra, .gallery {
            text-align: left;
            max-width: 800px;
            margin: 0 auto;
        }

        .product-description h3, .vision-mission h3 {
            margin-top: 1rem;
        }

        .gallery img {
            width: 100%;
            height: auto;
            margin: 0.5rem 0;
        }

        .about-extra img {
            max-width: 400px;
            margin: 1rem;
            display: inline-block;
        }

        .about-extra p {
            max-width: 400px;
            margin: 1rem auto;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1> CALAFISH </h1>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">Acerca de nosotros</a></li>
                <li><a href="#product">Producto</a></li>
                <li><a href="#gallery">Presentacion</a></li>
                <li><a href="#mission-vision">Visión y Misión</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Inicio</h2>
        <p>Descubre nuestros deliciosos nuggets de pota.</p>
        <!-- Imagen de nuggets de pota -->
        <img src="https://www.exalmar.com.pe/wp-content/uploads/2016/04/Esta-para-la-seccio%CC%81n-nuggets-arriba.jpg">
    </section>
    <section id="about">
        <h2>Acerca de</h2>
        <p>CALAFISH es una empresa que elabora un producto a base de pota en forma de barritas con sabor a mariscos empanizados en harina de maca y con relleno de huevera de pescado precocinados. Además, es un producto altamente nutritivo y de buen sabor capaz de satisfacer la necesidad de tener un excelente mantenimiento de la alimentación y la salud.</p>
        <!-- Imágenes adicionales en la sección "Acerca de nosotros" -->
        <div class="about-extra">
            <img src="file:///C:/Users/user/Pictures/bolbasor.jfif">
            <p>Descripción de la imagen adicional. Aquí puedes agregar más información o detalles sobre el proceso de producción o la empresa.</p>
        </div>
    </section>
    <section id="product">
        <h2>Descripción del Producto</h2>
        <div class="product-description">
            <img src="https://pbs.twimg.com/media/Ex_2PXwW8AYEBnK.jpg:large">
            <p>Nuestros nuggets de pota están elaborados con pota de alta calidad y una receta secreta que los hace irresistibles. Son ideales para cualquier ocasión, ya sea como aperitivo, en una comida rápida o para compartir con amigos y familia. Cada bocado es crujiente por fuera y tierno por dentro, ofreciendo una experiencia de sabor inigualable.</p>
            <h3>Características:</h3>
            <ul>
                <li>Hechos con ingredientes frescos y de alta calidad.</li>
                <li>Fácil y rápido de preparar.</li>
                <li>Ideal para niños y adultos.</li>
                <li>Empaque conveniente para su conservación.</li>
            </ul>
        </div>
    </section>
    <section id="presentation">
        <h2>Galería</h2>
        <div class="presentation">
            <img src="https://www.exalmar.com.pe/wp-content/uploads/2016/04/Esta-para-Seccio%CC%81n-CHD-Productos-abajo.png" alt="Galería Imagen 1">
            <img src="https://img.freepik.com/vector-gratis/ilustracion-calamar-dibujado-mano_23-2149594038.jpg" alt="Galería Imagen 2">
        </div>
    </section>
    <section id="mission-vision">
        <h2>Visión y Misión</h2>
        <div class="vision-mission">
            <h3>Visión</h3>
            <p>Para 2028, CALAFISH aspira a ser una de las principales exportadoras de productos marinos con altos estándares de calidad y sostenibilidad, destacándose a nivel internacional y promoviendo valores éticos en la industria.</p>
            <h3>Misión</h3>
            <p>Desarrollamos productos innovadores y de alta calidad con pota, promoviendo la responsabilidad social y generando valor económico, social y ambiental mediante la innovación y el compromiso con nuestros grupos de interés.
</p>
        </div>
    </section>
    <section id="contact">
        <h2>Contacto</h2>
        <p>Detalles de contacto para consultas sobre nuestros productos.</p>
        <p>Email: calafishexport@gmail.com</p>
        <p>Teléfono: +51 972945687</p>
        <p>Dirección: Av. Javier Prado Este 2499, San Borja 15036, Peru</p>
        <div class="social-media">
            <a href="https://facebook.com" target="_blank" title="Facebook">Facebook</a>
            <a href="https://twitter.com" target="_blank" title="Twitter">Twitter</a>
            <a href="https://instagram.com" target="_blank" title="Instagram">Instagram</a>
            <a href="https://linkedin.com" target="_blank" title="LinkedIn">LinkedIn</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 CALAFISH - Nuggets de Pota</p>
    </footer>
</body>
</html>
