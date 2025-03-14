# HTML-Page-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Commerce Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        /* Navigation Bar */
        .navbar {
            background-color: #333;
            overflow: hidden;
            padding: 15px;
            text-align: center;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: inline-block;
        }
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 50px;
            background-color: #ff9800;
            color: white;
            font-size: 24px;
        }

        /* Product Section */
        .products {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        .product-card {
            background-color: white;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 250px;
        }
        .product-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .buy-btn {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }
        .buy-btn:hover {
            background-color: #218838;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <div class="navbar">
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </div>

    <!-- Hero Section -->
    <div class="hero">
        <h1>Welcome to My E-Commerce Store</h1>
        <p>Shop the best products at the best prices!</p>
    </div>

    <!-- Product Section -->
    <div class="products">
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 1">
            <h3>Product 1</h3>
            <p>$19.99</p>
            <button class="buy-btn">Buy Now</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 2">
            <h3>Product 2</h3>
            <p>$24.99</p>
            <button class="buy-btn">Buy Now</button>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product 3">
            <h3>Product 3</h3>
            <p>$14.99</p>
            <button class="buy-btn">Buy Now</button>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>© 2025 My E-Commerce Store | Contact: info@myecommerce.com</p>
    </div>

</body>
</html>