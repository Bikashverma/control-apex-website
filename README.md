<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Control Apex Pvt. Ltd.</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <img src="logo.jpg" alt="Control Apex Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="home-section">
        <h1>Welcome to Control Apex Pvt. Ltd.</h1>
        <p>Your trusted elevator solution provider in Nepal</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services-section">
        <h2>Our Services</h2>
        <ul>
            <li>Passenger Lifts</li>
            <li>Hospital Lifts</li>
            <li>Home Lifts</li>
            <li>Goods Lifts</li>
            <li>Escalators</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>© 2024 Control Apex Pvt. Ltd. All rights reserved.</p>
    </footer>
</body>
</html>
