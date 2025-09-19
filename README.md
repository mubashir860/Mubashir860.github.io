<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mubashir Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #222;
      color: white;
      padding: 15px;
      text-align: center;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 10px;
      margin: 10px;
      padding: 15px;
      width: 200px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      max-width: 100%;
      border-radius: 5px;
    }
    button {
      background: #28a745;
      color: white;
      border: none;
      padding: 10px;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background: #218838;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Mubashir Store</h1>
    <p>Best products at best prices</p>
  </header>

  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 1">
      <h3>Product 1</h3>
      <p>Price: $10</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 2">
      <h3>Product 2</h3>
      <p>Price: $20</p>
      <button>Add to Cart</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200" alt="Product 3">
      <h3>Product 3</h3>
      <p>Price: $15</p>
      <button>Add to Cart</button>
    </div>
  </div>

  <footer>
    <p>&copy; 2025 Mubashir Store. All rights reserved.</p>
  </footer>

</body>
</html>
