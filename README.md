<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NIKOXA - Home</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e8f8f5; /* Light green background */
            color: #333;
        }

        /* Header Styles */
        header {
            background-color: #85c1e9; /* Light blue */
            color: white;
            padding: 1rem;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 1rem 0;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #b2d8b2; /* Light green hover effect */
        }

        /* Main Content Styles */
        main {
            padding: 1rem;
            text-align: center;
            background-color: white; /* White background for content */
            margin: 1rem auto;
            max-width: 90%;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }

        .product {
            background-color: #f5fcff; /* Very light blue */
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }

        .product:hover {
            transform: scale(1.05);
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .product h3 {
            margin: 0.5rem 0;
        }

        .product button {
            background-color: #85c1e9; /* Light blue button */
            color: white;
            border: none;
            padding: 0.5rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .product button:hover {
            background-color: #4CAF50; /* Green hover effect */
        }

        /* Footer Styles */
        footer {
            background-color: #b2d8b2; /* Light green */
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 1rem;
        }

        footer a {
            color: white;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>NIKOXA</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Catalogue</a></li>
                <li><a href="#">Cart</a></li>
                <li><a href="#">Checkout</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Welcome to NIKOXA</h2>
        <div class="product-grid">
            <!-- Repeat this block for more products -->
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 1">
                <h3>Product 1</h3>
                <p>$19.99</p>
                <button>View Details</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 2">
                <h3>Product 2</h3>
                <p>$29.99</p>
                <button>View Details</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </main>
    <footer>
        <p>Contact us: <a href="mailto:info@nikoxa.com">info@nikoxa.com</a></p>
        <p>All Rights Reserved © 2024 NIKOXA</p>
    </footer>
</body>
</html>
