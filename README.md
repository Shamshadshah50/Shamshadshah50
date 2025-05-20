<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MS Wall Company - Construction Products, Precast Boundary Walls</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background: url('https://i.imgur.com/KIBqT2h.png') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      position: relative;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
    }
    .btn {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #000;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    nav {
      position: absolute;
      top: 20px;
      left: 20px;
      right: 20px;
      display: flex;
      justify-content: space-between;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .product-list ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    .featured {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .card {
      background-color: #222;
      padding: 10px;
      flex: 1;
      min-width: 200px;
      text-align: center;
    }
    .contact {
      background-color: #000;
      padding: 20px;
    }
    .contact-info p {
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div><strong>MS Wall Company</strong></div>
      <div><a href="#contact" style="color: white; text-decoration: none;">Contact Us</a></div>
    </nav>
    <h1>Products for Construction</h1>
    <button class="btn">Get Started</button>
  </header>

  <section class="product-list">
    <h2>Our Products</h2>
    <ul>
      <li>High-quality concrete blocks</li>
      <li>Durable precast wall panels</li>
      <li>Versatile paving stones</li>
      <li>Reliable construction materials</li>
    </ul>
  </section>

  <section>
    <h2>Featured Products</h2>
    <div class="featured">
      <div class="card">
        <img src="https://i.imgur.com/fencingpole.png" alt="Fencing pole" width="100%">
        <p><strong>Fencing Pole</strong></p>
        <p>₹250/unit</p>
        <p>Details: Height 6 ft, Width 4 inch (4×4×6)</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/boundrywall.png" alt="Precast Boundary Wall" width="100%">
        <p><strong>Precast Boundary Wall</strong></p>
        <p>₹95/sq ft</p>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/paverblock.png" alt="Paving Stones" width="100%">
        <p><strong>Paving Stones</strong></p>
        <p>₹16/piece</p>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <div class="contact-info">
      <p><strong>Email:</strong> shahitradeservice@gmail.com</p>
      <p><strong>Phone:</strong> +91 8935005057</p>
      <p><strong>Address:</strong> Registered Office, Mulianic</p>
    </div>
  </section>
</body>
</html>
