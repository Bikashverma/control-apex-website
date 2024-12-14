<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Control Apex Pvt. Ltd.</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #007bff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        section {
            padding: 20px;
            background-color: white;
            margin: 20px 0;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #343a40;
            color: white;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #007bff;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<header>
    <h1>Control Apex Pvt. Ltd.</h1>
    <p>Leading Elevator Company in Nepal</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About Us</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>

<section>
    <h2>About Us</h2>
    <p>Control Apex Pvt. Ltd. is a leading elevator company in Nepal, with over 10 years of experience. We have installed 200 lifts and provide maintenance services for 150 lifts under AMC.</p>
</section>

<section>
    <h2>Our Services</h2>
    <ul>
        <li>Elevator Installation</li>
        <li>Maintenance and AMC</li>
        <li>Elevator Modernization</li>
        <li>Lift Supply (Indian, Chinese, Japanese Brands)</li>
    </ul>
</section>

<section>
    <h2>Contact Us</h2>
    <div class="contact-form">
        <form>
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <input type="tel" name="phone" placeholder="Your Phone" required>
            <input type="text" name="country" placeholder="Your Country" required>
            <input type="text" name="brand" placeholder="Brand Name" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Control Apex Pvt. Ltd. All Rights Reserved.</p>
</footer>

</body>
</html>
