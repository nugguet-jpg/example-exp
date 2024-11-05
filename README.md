<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bienvenido a Maxipizza Talca, encontrarás información de contacto y nuestros servicios.">
    <title>Maxipizza Talca</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <style>
        /* Basic Reset */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        /* Layout Styles */
        body {
            font-family: 'Roboto', sans-serif;
            color: #333;
            background-color: #f9f9f9;
            line-height: 1.6;
        }
        
        header {
            background-color: #b30000;
            color: #fff;
            padding: 1.5rem;
            text-align: center;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 700;
            transition: color 0.3s ease;
        }
        
        nav ul li a:hover {
            color: #ffd1d1;
        }
        
        main {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        section {
            margin: 2rem 0;
            padding: 1.5rem;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        section h2 {
            margin-bottom: 1rem;
            color: #b30000;
        }
        
        /* Responsive Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }
        
        .gallery img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        
        .gallery img:hover {
            transform: scale(1.05);
        }
        
        /* Contact Form */
        form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        
        form input, form textarea, form button {
            padding: 1rem;
            border: 1px solid #b30000;
            border-radius: 5px;
        }
        
        form button {
            background-color: #b30000;
            color: white;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        form button:hover {
            background-color: #990000;
        }
        
        footer {
            background-color: #800000;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Bienvenido a Maxipizza Talca</h1>
        <nav>
            <ul>
                <li><a href="#home">Bienvenido</a></li>
                <li><a href="#about">Acerca</a></li>
                <li><a href="#services">Servicios</a></li>
                <li><a href="#gallery">Galería</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <!-- Main Content -->
    <main>
        
        <!-- Home Section -->
        <section id="home">
            <h2>Bienvenidos a Maxipizza Talca</h2>
            <p>En Maxipizza Talca, la pasión por la buena comida se une a un ambiente acogedor. Ofrecemos una variedad deliciosa de pizzas elaboradas con ingredientes frescos y de alta calidad, junto con una selección de acompañamientos y postres irresistibles.</p>
        </section>
        
        <!-- About Section -->
        <section id="about">
            <h2>Acerca</h2>
            <p>Conoce más sobre Maxipizza Talca y nuestro compromiso de ofrecer una experiencia gastronómica única.</p>
        </section>
        
        <!-- Services Section -->
        <section id="services">
            <h2>Servicios</h2>
            <p>Explora nuestra oferta de servicios y productos, pensados para satisfacer todos los gustos.</p>
        </section>
        
        <!-- Gallery Section -->
        <section id="gallery">
            <h2>Galería</h2>
            <p>Descubre algunas de las delicias y el ambiente de Maxipizza Talca:</p>
            <div class="gallery">
                <img src="path/to/image1.jpg" alt="Imagen de una pizza deliciosa">
                <img src="path/to/image2.jpg" alt="Descripción de la imagen 2">
                <img src="path/to/image3.jpg" alt="Descripción de la imagen 3">
                <img src="path/to/image4.jpg" alt="Descripción de la imagen 4">
                <img src="path/to/image5.jpg" alt="Descripción de la imagen 5">
                <img src="path/to/image6.jpg" alt="Descripción de la imagen 6">
            </div>
        </section>
        
        <!-- Contact Section -->
        <section id="contact">
            <h2>Contacto</h2>
            <p>Ponte en contacto con nosotros usando el formulario a continuación.</p>
            <form>
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    
    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Maxipizza Talca. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
