<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Red-Themed Website</title>
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

        /* Contact Section */
        .contact-container {
            display: flex;
            flex-direction: row;
            gap: 20px;
            margin-top: 20px;
        }

        .qr-code {
            flex: 1;
            text-align: center;
            background-color: #fff0f0; /* Light red */
            padding: 10px;
            border: 1px solid #b30000;
            border-radius: 8px;
        }

        .qr-code img {
            width: 100px;
            height: 100px;
            margin-top: 10px;
        }

        form {
            flex: 2;
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
    </style>
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
