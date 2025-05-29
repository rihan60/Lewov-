<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Lewov Clothing Store</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="style.css" />
</head>
<body>
<header>
  <div class="logo">LEWOV</div>
  <nav>
    <a href="index.html" class="active">Home</a>
    <a href="products.html">Products</a>
    <a href="contact.html">Contact</a>
    <a href="about.html">About</a>
  </nav>
</header>

<section class="hero">
  <h1>Own The Look, Rule The Street</h1>
  <p>Explore our exclusive collection of Drop Shoulder Hoodies and stylish streetwear.</p>
  <div class="dress-animation">
    <!-- CSS animated dress shapes -->
    <div class="dress dress1"></div>
    <div class="dress dress2"></div>
    <div class="dress dress3"></div>
  </div>
</section>

<footer>
  &copy; 2025 Lewov. All rights reserved.
</footer>

<script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Products - Lewov</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="style.css" />
</head>
<body>
<header>
  <div class="logo">LEWOV</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="products.html" class="active">Products</a>
    <a href="contact.html">Contact</a>
    <a href="about.html">About</a>
  </nav>
</header>

<section class="products-section">
  <h2>Our Products</h2>
  <div class="product-list">
    <div class="product-card">
      <img src="images/drop-shoulder-hoodie.jpg" alt="Drop Shoulder Hoodie" />
      <h3>Drop Shoulder Hoodie</h3>
      <p>Comfortable, stylish drop shoulder hoodie made of 100% cotton.</p>
      <button>Buy Now</button>
    </div>
    <div class="product-card">
      <img src="images/casual-jacket.jpg" alt="Casual Jacket" />
      <h3>Casual Jacket</h3>
      <p>Lightweight jacket perfect for casual outings.</p>
      <button>Buy Now</button>
    </div>
    <div class="product-card">
      <img src="images/sporty-tee.jpg" alt="Sporty T-Shirt" />
      <h3>Sporty T-Shirt</h3>
      <p>Breathable and stylish T-shirt for everyday wear.</p>
      <button>Buy Now</button>
    </div>
    <!-- আরো প্রোডাক্ট যুক্ত করতে পারো -->
  </div>
</section>

<footer>
  &copy; 2025 Lewov. All rights reserved.
</footer>

<script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Contact - Lewov</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="style.css" />
</head>
<body>
<header>
  <div class="logo">LEWOV</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="products.html">Products</a>
    <a href="contact.html" class="active">Contact</a>
    <a href="about.html">About</a>
  </nav>
</header>

<section class="contact-section">
  <h2>Contact Us</h2>
  <form action="#" method="POST" class="contact-form">
    <label for="name">Full Name</label>
    <input type="text" id="name" name="name" required placeholder="Your full name" />
    
    <label for="email">Email Address</label>
    <input type="email" id="email" name="email" required placeholder="Your email" />
    
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required placeholder="Write your message here"></textarea>
    
    <button type="submit">Send Message</button>
  </form>

  <div class="contact-info">
    <h3>Our Store Location</h3>
    <p>123 Lewov Street, Dhaka, Bangladesh</p>
    <p>Email: support@lewov.com</p>
    <p>Phone: +880 1234 567890</p>
  </div>
</section>

<footer>
  &copy; 2025 Lewov. All rights reserved.
</footer>

<script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>About - Lewov</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="style.css" />
</head>
<body>
<header>
  <div class="logo">LEWOV</div>
  <nav>
    <a href="index.html">Home</a>
    <a href="products.html">Products</a>
    <a href="contact.html">Contact</a>
    <a href="about.html" class="active">About</a>
  </nav>
</header>

<section class="about-section">
  <h2>About Lewov</h2>
  <p>Lewov is a premium streetwear brand dedicated to quality, comfort, and style. Founded in 2023, our mission is to bring the best drop shoulder hoodies and trendy clothing to fashion lovers everywhere.</p>
  <p>We believe in sustainable fashion and empowering individuals through unique designs and premium materials.</p>
</section>

<footer>
  &copy; 2025 Lewov. All rights reserved.
</footer>

<script src="script.js"></script>
</body>
</html>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background-color: #d2b48c; /* light brown */
  color: #3a2e23;
}

header {
  background-color: #6b4c3b;
  color: #fdf6e3;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 30px;
  box-shadow: 0 3px 5px rgba(0,0,0,0.2);
}

.logo {
  font-size: 2rem;
  font-weight: 900;
  letter-spacing: 4px;
  text-shadow: 0 0 8px #f0c36d;
  animation: glow 3s ease-in-out infinite alternate;
  cursor: default;
}

@keyframes glow {
  from {
    text-shadow: 0 0 5px #f0c36d, 0 0 10px #f0c36d;
  }
  to {
    text-shadow: 0 0 20px #f0c36d, 0 0 30px #f0c36d;
  }
}

nav a {
  color: #fdf6e3;
  margin-left: 25px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: color 0.3s ease;
}

nav a:hover,
nav a.active {
  color: #fff9d0;
}

.hero {
  height: 75vh;
  background: url('https://images.unsplash.com/photo-1530845641357-3f3d1af8492f?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff8dc;
  text-shadow: 2px 2px 8px #4b3a28;
  animation: fadeIn 3s ease forwards;
  padding: 0 20px;
}

.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 15px;
}

.hero p {
  font-size: 1.4rem;
  max-width: 650px;
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity: 1;}
}

.dress-animation {
  margin-top: 30px;
  display: flex;
  gap: 40px;
  justify-content: center;
}

.dress {
  width: 120px;
  height: 180px;
  background: linear-gradient(135deg, #6b4c3b, #8c6e4b);
  border-radius: 20px 20px 40px 40px;
  position: relative;
  animation: float 4s ease-in-out infinite;
  box-shadow: 0 6px 10px rgba(0,0,0,0.3);
}

.dress1 {
  animation-delay: 0s;
}

.dress2 {
  animation-delay: 1.3s;
}

.dress3 {
  animation-delay: 2.6s;
}

@keyframes float {
  0%, 100% { transform: translateY(0);}
  50% { transform: translateY(-20px);}
}

.products-section,
.contact-section,
.about-section {
  padding: 40px 30px;
  max-width: 1100px;
  margin: auto;
  background-color: #f9f0e4cc;
  border-radius: 10px;
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
  margin-top: 30px;
}

.products-section h2,
.contact-section h2,
.about-section h2 {
  font-size: 2.5rem;
  margin-bottom: 25px;
  color: #5a3d1b;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: center;
}

.product-card {
  background: #fff;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  padding: 20px;
  width: 260px;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.product-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.25);
}

.product-card img {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 15px;
}

.product-card h3 {
  margin-bottom: 10px;
  color: #6b4c3b;
}

.product-card p {
  font-size: 0.9rem;
  margin-bottom: 15px;
  color: #7a5e3b;
}

.product-card button {
  background-color: #8c6e4b;
  border: none;
  color: white;
  padding: 10px 20px;
  font-weight: 700;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.product-card button:hover {
  background-color: #6b4c3b;
}

.contact-form {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  margin-bottom: 30px;
}

.contact-form label {
  margin-bottom: 6px;
  font-weight: 600;
  color: #5a3d1b;
}

.contact-form input,
.contact-form textarea {
  padding: 12px;
  border-radius: 8px;
  border: 1px solid #ccc;
  margin-bottom: 20px;
  font-size: 1rem;
  font-family: 'Poppins', sans-serif;
  resize: vertical;
}

.contact-form button {
  width: 150px;
  align-self: flex-start;
  background-color: #8c6e4b;
  border: none;
  color: white;
  padding: 12px;
  font-weight: 700;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.contact-form button:hover {
  background-color: #6b4c3b;
}

.contact-info h3 {
  margin-bottom: 12px;
  color: #5a3d1b;
}

footer {
  text-align: center;
  padding: 20px 0;
  background-color: #6b4c3b;
  color: #fdf6e3;
  margin-top: 40px;
  font-weight: 600;
}

@media (max-width: 768px) {
  .product-list {
    flex-direction: column;
    align-items: center;
  }
}
// এখানে খুব সহজ স্ক্রিপ্ট রাখলাম, যেমন ফর্ম সাবমিশন এ এলার্ট দিতে পারো

document.querySelector('form')?.addEventListener('submit', function (e) {
  e.preventDefault();
  alert('Thank you for contacting Lewov! We will get back to you soon.');
  this.reset();
});
