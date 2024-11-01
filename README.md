<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QR Code Contact Page</title>
    <style>
        body {
            background-color: red;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: white;
            color: black;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
        }
        .qr-code {
            margin-top: 20px;
        }
        .contact-info {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Contact Information</h1>
        <p>Scan the QR code below to get in touch with us!</p>
        
        <div class="qr-code">
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/4QAaRXhpZgAASUkqAAgAAAAHAAABBAABAAAA... (full base64 string here)" alt="QR Code" />
        </div>
        
        <div class="contact-info">
            <h2>Contact Us</h2>
            <p>Email: example@example.com</p>
            <p>Phone: (123) 456-7890</p>
            <p>Address: 1234 Example St, City, Country</p>
        </div>
    </div>
</body>
</html>
