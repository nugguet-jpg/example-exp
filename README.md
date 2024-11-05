<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bienvenido a Maxipizza Talca, el mejor lugar para disfrutar de deliciosas pizzas en un ambiente acogedor.">
    <title>Maxipizza Talca</title>
    
    <!-- Fonts and CSS Reset -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    
    <style>
        /* Basic Reset and Font */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Roboto', sans-serif; color: #333; line-height: 1.6; background-color: #f5f5f5; }
        
        /* Header Styles */
        header {
            background-color: #b30000;
            color: #fff;
            padding: 2rem 1rem;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            gap: 1rem;
            margin-top: 1rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: 700;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffd1d1;
        }
        
        /* Hero Section */
        .hero {
            background: url('path/to/hero-image.jpg') no-repeat center center/cover;
            color: #fff;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 2rem;
        }

        .hero h2 {
            font-size: 2.5rem;
            background: rgba(0, 0, 0, 0.5);
            padding: 1rem;
            border-radius: 10px;
        }

        /* General Section Styles */
        section {
            padding: 2rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        section h2 {
            text-align: center;
            color: #b30000;
            margin-bottom: 1rem;
            font-size: 2rem;
        }

        .content {
            display: grid;
            grid-template-columns: 1fr;
            gap: 1rem;
        }

        /* Menu Section */
        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            text-align: center;
        }

        .menu-item {
            background-color: #fff;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .menu-item h3 {
            color: #b30000;
            margin-bottom: 0.5rem;
        }

        .menu-item p {
            color: #555;
        }

        /* Testimonials Section */
        .testimonials {
            background-color: #f9f9f9;
            padding: 2rem 1rem;
        }

        .testimonial-item {
            background-color: #fff;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 1rem 0;
        }

        .testimonial-item h4 {
            color: #b30000;
        }

        .testimonial-item p {
            font-style: italic;
            color: #555;
        }

        /* FAQs Section */
        .faq {
            background-color: #fff;
            padding: 2rem 1rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .faq-item h4 {
            color: #b30000;
            margin-bottom: 0.5rem;
        }

        /* Footer */
        footer {
            background-color: #800000;
            color: #fff;
            text-align: center;
            padding: 1.5rem;
            margin-top: 2rem;
        }

        footer p {
            margin: 0.5rem 0;
        }

        .social-icons a {
            color: #fff;
            margin: 0 0.5rem;
            text-decoration: none;
            font-size: 1.2rem;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Maxipizza Talca</h1>
        <nav>
            <ul>
                <li><a href="#about">Acerca</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#testimonials">Testimonios</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <!-- Hero Section -->
    <section class="hero">
        <h2>La mejor pizza en Talca</h2>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>Sobre Nosotros</h2>
        <p>Maxipizza Talca se enorgullece de ofrecer pizzas deliciosas y frescas con ingredientes de alta calidad. Nuestro equipo está dedicado a brindar la mejor experiencia gastronómica en un ambiente acogedor.</p>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Menú</h2>
        <div class="menu">
            <div class="menu-item">
                <h3>Pizza Margherita</h3>
                <p>Queso mozzarella, tomate, albahaca fresca.</p>
            </div>
            <div class="menu-item">
                <h3>Pizza Pepperoni</h3>
                <p>Queso mozzarella, pepperoni, orégano.</p>
            </div>
            <div class="menu-item">
                <h3>Pizza Vegetariana</h3>
                <p>Queso mozzarella, tomate, pimientos, champiñones, cebolla.</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <h2>Testimonios</h2>
        <div class="testimonial-item">
            <h4>Juan P.</h4>
            <p>"La mejor pizza que he probado en Talca. Ingredientes frescos y un ambiente genial."</p>
        </div>
        <div class="testimonial-item">
            <h4>María R.</h4>
            <p>"Un servicio increíble y la pizza vegetariana es deliciosa."</p>
        </div>
    </section>

    <!-- FAQs Section -->
    <section id="faq">
        <h2>Preguntas Frecuentes</h2>
        <div class="faq">
            <div class="faq-item">
                <h4>¿Realizan entregas a domicilio?</h4>
                <p>Sí, ofrecemos servicio a domicilio en toda la ciudad de Talca.</p>
            </div>
            <div class="faq-item">
                <h4>¿Tienen opciones vegetarianas y sin gluten?</h4>
                <p>¡Claro! Contamos con una variedad de opciones vegetarianas y opciones sin gluten.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contacto</h2>
        <p>Puedes contactarnos a través de nuestro formulario o en nuestras redes sociales.</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Maxipizza Talca. Todos los derechos reservados.</p>
        <div class="social-icons">
            <a href="https://facebook.com" target="_blank">Facebook</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
        </div>
    </footer>

</body>
</html>
