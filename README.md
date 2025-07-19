# SweetAngelBakes-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sweet Bites | Cookies & Donuts</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fff8f2;
      color: #4b2e2e;
      line-height: 1.6;
    }
    header {
      background-color: #f28c28;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }
    header h1 {
      font-size: 3em;
    }
    nav {
      background-color: #ffd9b3;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      margin: 0 20px;
      color: #4b2e2e;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }
    .product {
      background-color: white;
      border: 1px solid #e4c7a5;
      border-radius: 15px;
      width: 260px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background-color: #f28c28;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sweet Bites</h1>
    <p>Freshly Baked Cookies & Donuts for Every Craving!</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#products">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to Sweet Bites</h2>
    <p>We mix love and sweetness in every bite. Handcrafted cookies and donuts made fresh daily just for you.</p>
  </section>

  <section id="products">
    <h2>Our Sweet Picks</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x160.png?text=Chocolate+Chip+Cookie" alt="Chocolate Chip Cookie" />
        <h3>Chocolate Chip Cookie</h3>
        <p>Soft and chewy with rich chocolate chips in every bite.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x160.png?text=Classic+Glazed+Donut" alt="Classic Glazed Donut" />
        <h3>Classic Glazed Donut</h3>
        <p>Golden, fluffy, and perfectly glazed — a timeless favorite.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x160.png?text=Red+Velvet+Cookie" alt="Red Velvet Cookie" />
        <h3>Red Velvet Cookie</h3>
        <p>Sweet, rich, and filled with white chocolate chips.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Sweet Bites started with a dream — to share joy through every dessert. We use only the best ingredients and bake everything fresh each morning.</p>
  </section>

  <section id="contact">
    <h2>Get in Touch</h2>
    <p>Email: hello@sweetbites.com<br>
    Phone: (123) 456-7890<br>
    Facebook & Instagram: @SweetBitesPH</p>
  </section>

  <footer>
    &copy; 2025 Sweet Bites. All rights reserved. Designed with love.
  </footer>
</body>
</html>
