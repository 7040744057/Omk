<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OM LES – Wear Your Style</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: #fff;
      color: #222;
    }
    header {
      text-align: center;
      padding: 20px;
      background: #000;
      color: #fff;
      font-size: 28px;
      font-weight: 600;
      letter-spacing: 2px;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 30px;
      max-width: 1100px;
      margin: auto;
    }
    .product {
      background: #f8f8f8;
      border-radius: 16px;
      text-align: center;
      padding: 20px;
      transition: 0.3s;
    }
    .product:hover {
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      transform: translateY(-5px);
    }
    .product img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 12px;
    }
    .product h3 {
      margin: 15px 0 5px;
      font-size: 20px;
    }
    .price {
      font-size: 18px;
      font-weight: bold;
      color: #e63b7a;
    }
    button {
      margin-top: 10px;
      padding: 10px 25px;
      background: #000;
      color: #fff;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background: #e63b7a;
    }
  </style>
</head>
<body>

<header>OM LES – Wear Your Style</header>

<section class="container">

  <div class="product">
    <img src="tshirt.jpg" alt="OM LES T-shirt" />
    <h3>Stylish T-Shirt</h3>
    <p class="price">₹500</p>
    <button onclick="alert('Thank you for choosing OM LES!')">Buy Now</button>
  </div>

  <div class="product">
    <img src="jeans.jpg" alt="OM LES Jeans" />
    <h3>Classic Jeans</h3>
    <p class="price">₹500</p>
    <button onclick="alert('Thank you for choosing OM LES!')">Buy Now</button>
  </div>

  <div class="product">
    <img src="hoodie.jpg" alt="OM LES Hoodie" />
    <h3>Cozy Hoodie</h3>
    <p class="price">₹500</p>
    <button onclick="alert('Thank you for choosing OM LES!')">Buy Now</button>
  </div>

</section>

</body>
</html>
