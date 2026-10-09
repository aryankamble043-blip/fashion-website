# fashion-website
My first free fashion website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Fashion Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fffaf7;
      color: #292323;
      text-align: center;
    }
    header {
      background: #292323;
      color: white;
      padding: 24px 12px;
    }
    header h1 {
      margin: 0;
      letter-spacing: 3px;
    }
    nav {
      background: #e8d8cf;
      padding: 12px;
    }
    nav a {
      color: #292323;
      text-decoration: none;
      margin: 0 10px;
    }
    .hero {
      padding: 45px 15px;
      background: #f2e4dc;
    }
    .hero h2 {
      font-size: 30px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 18px;
      padding: 20px;
    }
    .product {
      background: white;
      border-radius: 12px;
      padding: 15px;
      width: 145px;
      box-shadow: 0 2px 8px #ddd;
    }
    .product .emoji {
      font-size: 65px;
      background: #f7eee9;
      padding: 15px 0;
      border-radius: 8px;
    }
    .product p {
      margin: 8px 0;
    }
    .button {
      display: inline-block;
      background: #237447;
      color: white;
      padding: 12px 18px;
      text-decoration: none;
      border-radius: 6px;
      margin-top: 10px;
    }
    footer {
      background: #292323;
      color: white;
      padding: 20px;
      margin-top: 25px;
    }
  </style>
</head>
<body>
  <header>
    <h1>MY FASHION STORE</h1>
    <p>Your Style, Your Choice</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h2>Discover Your Style</h2>
    <p>Fashion that makes you feel amazing.</p>
    <a href="#products" class="button">Shop Now</a>
  </section>

  <h2 id="products">Our Collection</h2>

  <section class="products">
    <div class="product">
      <div class="emoji">👕</div>
      <h3>Classic T-Shirt</h3>
      <p>₹499</p>
    </div>
    <div class="product">
      <div class="emoji">👗</div>
      <h3>Stylish Dress</h3>
      <p>₹999</p>
    </div>
    <div class="product">
      <div class="emoji">🧥</div>
      <h3>Fashion Jacket</h3>
      <p>₹1,499</p>
    </div>
  </section>

  <section id="contact">
    <h2>Want to Order?</h2>
    <p>Contact us on WhatsApp!</p>
    <a class="button"
       href="https://wa.me/91YOURNUMBER">
      Order on WhatsApp
    </a>
    <p>Replace YOURNUMBER with your WhatsApp number.</p>
  </section>

  <footer>
    <p>© 2026 My Fashion Store</p>
    <p>Made with love ❤️</p>
  </footer>
</body>
</html>
