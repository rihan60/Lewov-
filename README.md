<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lewov - Premium Streetwear</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f1ee;
      color: #333;
    }
    header {
      background: #1a1a1a;
      padding: 20px 40px;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      animation: slideDown 1s ease;
    }
    @keyframes slideDown {
      from { transform: translateY(-100%); }
      to { transform: translateY(0); }
    }
    .logo {
      font-family: 'Orbitron', sans-serif;
      font-size: 2rem;
      color: #fff;
      letter-spacing: 2px;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      height: 70vh;
      position: relative;
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    .hero video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    .hero h2 {
      font-size: 3rem;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
      animation: fadeIn 2s ease;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .description {
      padding: 40px;
      background: white;
      text-align: center;
    }
    .description h3 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .description p {
      font-size: 1.1rem;
      line-height: 1.6;
      max-width: 800px;
      margin: auto;
    }
    .slider {
      background: #000;
      color: #fff;
      overflow: hidden;
      white-space: nowrap;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    .slider-text {
      display: inline-block;
      padding: 15px 0;
      font-weight: 600;
      font-size: 1rem;
      animation: marquee 20s linear infinite;
    }
    @keyframes marquee {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">LEWOV</div>
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <div class="slider">
    <div class="slider-text">
      New Drop Available Now — Black Signature Hoodie | White Oversized Tee | Classic Full Sleeve — Shop Fast Before Sold Out!
    </div>
  </div>

  <section class="hero">
    <video autoplay muted loop>
      <source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
      Your browser does not support HTML5 video.
    </video>
    <h2>Own the Look. Rule the Street.</h2>
  </section>

  <section class="description">
    <h3>About Lewov</h3>
    <p>Lewov is a premium streetwear brand designed for modern trendsetters. We combine edgy designs, high-quality materials, and unmatched comfort to create pieces that empower your presence. Whether you're hitting the streets or chilling with friends, Lewov makes sure you do it in style.</p>
  </section>

  <footer>
    <p>&copy; 2025 Lewov. All Rights Reserved.</p>
  </footer>
</body>
</html>
