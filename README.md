<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bienvenido a Maxipizza Talca, encontraras informacion de contacto y nuestros servicios.">
    <title>Maxipizza Talca</title>
    <style>
        /* Inline CSS for demonstration */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #ffe6e6; /* Light red background */
        }

        header {
            background-color: #b30000; /* Dark red */
            color: white;
            padding: 1rem;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        main {
            padding: 1rem;
            background-color: #ffe6e6; /* Light red background for content */
        }

        section {
            margin: 20px 0;
            background-color: white;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #b30000; /* Dark red */
        }

        form {
            display: flex;
            flex-direction: column;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        form label {
            margin: 8px 0 4px;
            color: #b30000; /* Dark red for labels */
        }

        form input, form textarea, form button {
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #b30000;
            border-radius: 4px;
        }

        form button {
            background-color: #b30000;
            color: white;
            cursor: pointer;
        }

        form button:hover {
            background-color: #990000;
        }

        footer {
            background-color: #800000; /* Maroon */
            color: white;
            text-align: center;
            padding: 1rem;
        }

        /* Image Gallery Styles */
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* Three columns */
            gap: 10px;
        }

        .gallery img {
            width: 100%; /* Make images responsive */
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <!-- Header Section -->
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
            <p>En Maxipizza Talca, la pasión por la buena comida se une a un ambiente acogedor. Ofrecemos una variedad deliciosa de pizzas elaboradas con ingredientes frescos y de alta calidad, junto con una selección de acompañamientos y postres irresistibles. Ya sea para una cena familiar, una reunión con amigos o un antojo personal, en Maxipizza encontrarás el sabor perfecto que te hará regresar una y otra vez. Además, invitamos a quienes estén interesados en colaborar o hacer negocios con nosotros a acceder a nuestra carta y obtener más información sobre nuestras oportunidades. ¡Ven y disfruta de una experiencia gastronómica única!</p>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>Acerca</h2>
            <p>Esta sección proporciona información sobre Maxipizza Talca y lo que ofrecemos.</p>
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Servicios</h2>
            <p>Aquí puedes listar los servicios o productos que ofrecemos en Maxipizza Talca.</p>
        </section>

        <!-- Gallery Section -->
        <section id="gallery">
            <h2>Galería</h2>
            <p>Mira algunas imágenes de Maxipizza Talca:</p>
            <div class="gallery">
                <img src="path/to/image1.jpg" alt="Descripción de la imagen 1">
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
            <p>Ponte en contacto utilizando el formulario a continuación.</p>
            
            <!-- Contact Form -->
            <form>
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Enviar</button>
            </form>

            <p>Si lo prefieres, también puedes contactarme a través de <a href="https://wa.me/c/56962454596" target="_blank">WhatsApp</a>.</p>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Maxipizza Talca. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

