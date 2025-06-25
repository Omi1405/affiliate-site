# affiliate-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>amazon_apb deals</title>
  <style>
    :root {
      --primary-color: #ff9900;
      --secondary-color: #131921;
      --text-dark: #111;
      --text-light: #fff;
      --hover-color: #e6b800;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      color: #222;
    }

    /* Navbar */
    .navbar {
      background-color: var(--secondary-color);
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
      padding: 12px 24px;
      color: var(--text-light);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
      color: var(--primary-color);
    }

    .search-box {
      flex: 1;
      margin: 0 20px;
      max-width: 500px;
    }

    .search-box input {
      width: 100%;
      padding: 8px 14px;
      border-radius: 4px;
      border: none;
      outline: none;
      font-size: 1rem;
    }

    .nav-links a {
      margin: 0 10px;
      color: var(--text-light);
      text-decoration: none;
      font-weight: 500;
      transition: 0.3s;
    }

    .nav-links a:hover {
      text-decoration: underline;
      color: var(--primary-color);
    }

    /* Product Grid */
    .product-container {
      padding: 30px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 25px;
      max-width: 1200px;
      margin: auto;
    }

    .product {
      background-color: #fff;
      border-radius: 10px;
      padding: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      max-height: 200px;
      object-fit: contain;
      margin-bottom: 12px;
    }

    .product h3 {
      font-size: 1.05rem;
      font-weight: 600;
      min-height: 48px;
      margin: 10px 0;
    }

    .price {
      color: #b12704;
      font-size: 1.1rem;
      font-weight: bold;
    }

    .original-price {
      text-decoration: line-through;
      color: #565959;
      font-size: 0.9rem;
      margin-left: 8px;
    }

    .discount {
      color: #007600;
      font-size: 0.9rem;
      margin-top: 4px;
    }

    .product a {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 16px;
      background-color: var(--primary-color);
      color: var(--text-dark);
      font-weight: bold;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }

    .product a:hover {
      background-color: var(--hover-color);
    }

    footer {
      background-color: var(--secondary-color);
      color: var(--text-light);
      text-align: center;
      padding: 20px;
      font-size: 0.95rem;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      .search-box {
        margin-top: 10px;
        width: 100%;
      }

      .nav-links {
        margin-top: 10px;
        text-align: center;
        width: 100%;
      }

      .nav-links a {
        display: inline-block;
        margin: 5px 10px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header class="navbar">
    <div class="logo">amazon_<span style="color:#fff">apb</span> <span style="color:#ff9900">deals</span></div>
    <div class="search-box">
      <input type="text" placeholder="Search products... (Coming soon)">
    </div>
    <nav class="nav-links">
      <a href="#">Home</a>
      <a href="#">Electronics</a>
      <a href="#">Mobiles</a>
      <a href="#">Laptops</a>
      <a href="#">Accessories</a>
    </nav>
  </header>

  <!-- Product Section -->
  <main class="product-container">
    <!-- Product 1 -->
    <div class="product">
      <img src="https://m.media-amazon.com/images/I/71JwKnROg8L._SX679_.jpg" alt="Samsung Monitor">
      <h3>Samsung 22&quot; FHD Borderless Monitor</h3>
      <div class="price">₹6,499 <span class="original-price">₹11,500</span></div>
      <div class="discount">43% off</div>
      <a href="https://amzn.to/4nk28Bo" target="_blank">Buy Now</a>
    </div>

    <!-- Product 2 -->
    <div class="product">
      <img src="https://m.media-amazon.com/images/I/71n0H0O4LFL._SL1500_.jpg" alt="Noise Smartwatch">
      <h3>Noise ColorFit Pulse Grand Smart Watch</h3>
      <div class="price">₹1,499 <span class="original-price">₹2,999</span></div>
      <div class="discount">50% off</div>
      <a href="https://www.amazon.in/dp/B09NRK1GMC?tag=amazonafb-21" target="_blank">Buy Now</a>
    </div>

    <!-- Product Template -->
    <div class="product">
      <img src="https://m.media-amazon.com/images/I/31-rF5rB3UL._SX300_SY300_QL70_FMwebp_.jpg" alt="Keyboard">
      <h3>Product Title</h3>
      <div class="price">₹PRICE <span class="original-price">₹OLD_PRICE</span></div>
      <div class="discount">XX% off</div>
      <a href="AMAZON_AFFILIATE_LINK" target="_blank">Buy Now</a>
    </div>

    <!-- Add more product blocks by duplicating the above -->
  </main>

  <!-- Footer -->
  <footer>
    © 2025 amazon_apb deals. This site contains affiliate links to Amazon.in. As an Amazon Associate, we earn from qualifying purchases.
  </footer>

</body>
</html>
