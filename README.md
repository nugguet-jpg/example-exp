  <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maxipizza Talca</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <style>
        /* General Styling */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Roboto', sans-serif; color: #333; background-color: #f5f5f5; }

        /* Header */
        header {
            background-color: #b30000;
            color: #fff;
            padding: 2rem 1rem;
            text-align: center;
        }
        header h1 { font-size: 2.5rem; }

        /* Navigation */
        nav ul { display: flex; justify-content: center; list-style: none; gap: 1.5rem; margin-top: 1rem; }
        nav ul li a {
            color: #fff; text-decoration: none; font-weight: 700;
            transition: color 0.3s;
        }
        nav ul li a:hover { color: #ffd1d1; }

        /* Hero Section */
        .hero { background: url('path/to/hero-image.jpg') no-repeat center center/cover; color: #fff; height: 60vh; display: flex; align-items: center; justify-content: center; text-align: center; padding: 2rem; }
        .hero h2 { font-size: 2.5rem; background: rgba(0, 0, 0, 0.5); padding: 1rem; border-radius: 10px; }

        /* Section Layout */
        section {
            padding: 2rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
            margin-bottom: 2rem;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        section h2 { text-align: center; color: #b30000; margin-bottom: 1.5rem; font-size: 2rem; }

        /* Menu Section */
        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Increased column minimum for larger items */
            gap: 1.5rem;
        }
        .menu-item {
            background-color: #fff;
            padding: 2rem; /* Increased padding for larger cards */
            border-radius: 8px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            text-align: center;
            font-size: 1.1rem; /* Slightly larger text */
            transition: transform 0.3s;
        }
        .menu-item:hover {
            transform: scale(1.05); /* Slight zoom effect on hover */
        }
        .menu-item h3 { color: #b30000; margin-bottom: 0.5rem; }

        /* Testimonials */
        .testimonials {
            background: #f9f9f9;
            padding: 2rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }
        .testimonial-item {
            padding: 1.5rem;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Contact Form */
        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #b30000;
        }

        /* Footer */
        footer {
            background: #800000;
            color: #fff;
            text-align: center;
            padding: 1.5rem;
        }
        .footer-socials a {
            color: #fff; text-decoration: none; margin: 0 0.5rem;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Maxipizza Talca</h1>
        <nav>
            <ul>
                <li><a href="#about">Acerca</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#testimonials">Testimonios</a></li>
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
        <p>Maxipizza Talca ofrece una experiencia gastronómica única, con pizzas frescas y deliciosas en un ambiente acogedor.</p>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Nuestro Menú</h2>
        <div class="menu">
            <div class="menu-item">
                <h3>Pizza Margherita</h3>
                <p>Queso mozzarella, tomate, albahaca fresca.</p>
            </div>
            <div class="menu-item">
                <h3>Pizza Pepperoni</h3>
                <p>Queso mozzarella, pepperoni, orégano.</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2>Testimonios</h2>
        <div class="testimonials">
            <div class="testimonial-item">
                <h4>Juan P.</h4>
                <p>"La mejor pizza en Talca, ingredientes frescos y ambiente acogedor."</p>
            </div>
            <div class="testimonial-item">
                <h4>María R.</h4>
                <p>"Un servicio excelente y una pizza deliciosa."</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contacto</h2>
        <form class="contact-form">
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo Electrónico" required>
            <textarea rows="4" placeholder="Mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Maxipizza Talca. Todos los derechos reservados.</p>
        <div class="footer-socials">
            <a href="#">Facebook</a> | <a href="#">Instagram</a> | <a href="#">Twitter</a>
        </div>
    </footer>

</body>
</html>
