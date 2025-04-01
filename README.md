<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Commerce Store</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            background: #e0e0e0;
        }

        /* Navbar */
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            width: 100%;
            z-index: 1000;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
        }

        /* Sections */
        section {
            padding: 50px;
            text-align: center;
        }

        .section-content {
            display: flex;
            justify-content: space-evenly;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .box {
            width: 250px;
            height: 250px;
            border-radius: 8px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            font-weight: bold;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .box1 { background: #ff5733; }
        .box2 { background: #33aaff; }
        .box3 { background: #33cc77; }
        .box4 { background: #ffcc33; }

        /* Registration Section */
        .registration-section {
            background: #fff;
            padding: 50px;
            text-align: center;
        }

        .registration-section form {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: auto;
        }

        .registration-section input {
            margin: 10px 0;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .registration-section button {
            background: #007bff;
            color: white;
            padding: 12px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            margin-top: 10px;
            border-radius: 5px;
        }

        .registration-section button:hover {
            background: #0056b3;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 40px;
            margin-top: 50px;
        }

        .footer-content {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
        }

        .footer-column {
            max-width: 300px;
            text-align: left;
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <header>
        <div class="logo">
            <img src="https://via.placeholder.com/50" alt="Logo">
            <h1>My Store</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#electronics">Electronics</a></li>
                <li><a href="#clothing">Clothing</a></li>
                <li><a href="#accessories">Accessories</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sections -->
    <section id="electronics">
        <h2>Electronics</h2>
        <p>Latest gadgets and devices at the best prices!</p>
        <div class="section-content">
            <div class="box box1">Smartphones</div>
            <div class="box box2">Laptops</div>
            <div class="box box3">Tablets</div>
            <div class="box box4">Headphones</div>
        </div>
    </section>

    <section id="clothing">
        <h2>Clothing</h2>
        <p>Trendy and comfortable clothing for everyone.</p>
        <div class="section-content">
            <div class="box box1">Shirts</div>
            <div class="box box2">Pants</div>
            <div class="box box3">Jackets</div>
            <div class="box box4">Shoes</div>
        </div>
    </section>

    <section id="accessories">
        <h2>Accessories</h2>
        <p>Complete your style with our best accessories.</p>
        <div class="section-content">
            <div class="box box1">Watches</div>
            <div class="box box2">Bags</div>
            <div class="box box3">Jewelry</div>
            <div class="box box4">Sunglasses</div>
        </div>
    </section>

    <!-- Registration Section -->
    <section class="registration-section">
        <h2>User Registration</h2>
        <p>Sign up to get access to exclusive deals and offers!</p>
        <form>
            <input type="text" placeholder="Full Name" required>
            <input type="email" placeholder="Email Address" required>
            <input type="password" placeholder="Password" required>
            <input type="password" placeholder="Confirm Password" required>
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-column">
                <h3>About Us</h3>
                <p>We are a leading e-commerce platform providing high-quality products at great prices.</p>
            </div>
            <div class="footer-column">
                <h3>Contact Us</h3>
                <p>Email: support@myonlinestore.com</p>
                <p>Phone: +123-456-7890</p>
            </div>
            <div class="footer-column">
                <h3>Follow Us</h3>
                <p>Facebook | Twitter | Instagram</p>
            </div>
        </div>
        <p>© 2025 My Online Store</p>
    </footer>

</body>
</html>
