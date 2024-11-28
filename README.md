<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NIKOXA - Home</title>
    <link rel="stylesheet" href="styles.css">
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
        <h2>Welcome to NIKOXA</h2>
        <div class="product-grid">
            <!-- Repeat this block for 25 products -->
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 1">
                <h3>Product 1</h3>
                <p>$19.99</p>
                <button>View Details</button>
            </div>
            <!-- Add 24 more product blocks here -->
        </div>
    </main>
    <footer>
        <p>Contact us: <a href="mailto:info@nikoxa.com">info@nikoxa.com</a></p>
        <p>All Rights Reserved © 2024 NIKOXA</p>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #e8f8f5; /* Light green background */
    color: #333;
    background-image: url('sky.png '); /* Replace with the actual path to your image */
    background-size: 100px; /* sky.png */
    background-repeat: no-repeat;
    background-position: bottom right; /* Positioned at the bottom-right */
}

/* Header Styles */
header {
    background-color: #b2d8b2; /* Very light green */
    color: white;
    padding: 1rem;
    text-align: center;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
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
    gap: 20px;
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
    background-color: #85c1e9; /* Light blue hover effect */
}

/* Main Styles */
main {
    padding: 2rem;
    background-color: white; /* White background for the main section */
    border-radius: 10px;
    margin: 2rem;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

main h2 {
    text-align: center;
    color: #4CAF50; /* Green title */
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1rem;
    padding: 1rem;
}

.product {
    background: #f5fcff; /* Very light blue */
    padding: 1rem;
    border: 1px solid #ddd;
    text-align: center;
    border-radius: 5px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product:hover {
    transform: scale(1.05);
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
}

.product img {
    max-width: 100%;
    height: auto;
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

/* Footer Styles */
footer {
    background-color: #85c1e9; /* Light blue */
    color: white;
    text-align: center;
    padding: 1rem;
    position: relative;
    bottom: 0;
    width: 100%;
    border-top: 5px solid #4CAF50; /* Green border */
}

footer a {
    color: #e8f8f5; /* Very light green link */
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
