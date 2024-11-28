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
            background-color: #b2d8b2; /* Light green */
            color: white;
            text-align: center;
            padding: 1rem;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 15px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: white;
            color: #4CAF50; /* Green hover text */
        }

        /* Main Section */
        main {
            padding: 2rem;
            text-align: center;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }

        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .product img {
            max-width: 100%;
            border-radius: 5px;
        }

        button {
            background-color: #4CAF50; /* Green button */
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #45a049;
        }

        /* Footer */
        footer {
            background-color: #b2d8b2; /* Light green */
            color: white;
            text-align: center;
            padding: 1rem;
        }

        footer a {
            color: white;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>NIKOXA</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="catalogue.html">Catalogue</a></li>
                <li><a href="cart.html">Cart</a></li>
                <li><a href="checkout.html">Checkout</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Welcome to NIKOXA, Your Favorite Traditional Clothing Store</h2>
        <div class="product-grid">
            <!-- Display 10 Products -->
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
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 3">
                <h3>Product 3</h3>
                <p>$39.99</p>
                <button>View Details</button>
            
                <img src="https://via.placeholder.com/150" alt="Product 6">
                <h3>Product 6</h3>
                <p>$69.99</p>
                <button>View Details</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 7">
                <h3>Product 7</h3>
                <p>$79.99</p>
                <button>View Details</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 8">
                <h3>Product 8</h3>
                <p>$89.99</p>
                <button>View Details</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 9">
                <h3>Product 9</h3>
                <p>$99.99</p>
                <button>View Details</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 10">
                <h3>Product 10</h3>
                <p>$109.99</p>
                <button>View Details</button>
            </div>
        </div>
    </main>
    <footer>
        <p>Contact us: <a href="mailto:info@nikoxa.com">info@nikoxa.com</a></p>
        <p>All Rights Reserved © 2024 NIKOXA</p>
    </footer>
</body>
</html>
