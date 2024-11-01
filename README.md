<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Red-Themed Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Red-Themed Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of my red-themed website.</p>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>About</h2>
            <p>This section provides information about me or my website.</p>
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Services</h2>
            <p>Here you can list the services or products you offer.</p>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact</h2>
            <p>Get in touch using the form below or scan the QR code to reach us directly.</p>
            
            <div class="contact-container">
                <!-- QR Code Placeholder -->
                <div class="qr-code">
                    <p>Scan this QR code:</p>
                    <img src="qr-code-placeholder.png" alt="QR Code" />
                </div>

                <!-- Contact Form -->
                <form>
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>

                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>

                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>

                    <button type="submit">Submit</button>
                </form>
            </div>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 My Red-Themed Website. All rights reserved.</p>
    </footer>
</body>
</html>
