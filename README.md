# Hut
Bakery 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cravings Hut</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #fff5f8;
    text-align: center;
}

header {
    background: linear-gradient(to right, #ff69b4, #ff1493);
    color: white;
    padding: 25px;
}

nav {
    background: #ff1493;
    padding: 12px;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

.section {
    padding: 50px 20px;
}

.hero {
    background: #ffe4ec;
    padding: 60px 20px;
}

.button {
    background: #ff1493;
    color: white;
    padding: 12px 25px;
    border-radius: 25px;
    text-decoration: none;
    display: inline-block;
    margin-top: 15px;
}

.card {
    background: white;
    padding: 15px;
    margin: 20px;
    border-radius: 15px;
    display: inline-block;
    width: 280px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

.stars {
    color: gold;
}

form input, form textarea {
    width: 80%;
    padding: 10px;
    margin: 8px;
    border-radius: 8px;
    border: 1px solid #ccc;
}

form button {
    background: #ff1493;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 20px;
}

footer {
    background: #ff1493;
    color: white;
    padding: 20px;
}
</style>
</head>

<body>

<header>
<h1>Cravings Hut 🎂</h1>
<p>Premium Custom Cakes in India</p>
</header>

<nav>
<a href="#home">Home</a>
<a href="#cakes">Cakes</a>
<a href="#gallery">Gallery</a>
<a href="#reviews">Reviews</a>
<a href="#order">Order</a>
<a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
<h2>Making Every Celebration Sweeter 💕</h2>
<p>Birthday | Wedding | Baby Shower | Engagement</p>
<a href="#order" class="button">Place an Order</a>
</div>

<div class="section" id="cakes">
<h2>Our Signature Cakes</h2>

<div class="card">
<img src="https://images.unsplash.com/photo-1605475128021-4d7e8d7c0e10">
<h3>Chocolate Truffle</h3>
<p>₹899</p>
<div class="stars">★★★★★</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1621303837174-89787a7d4729">
<h3>Red Velvet</h3>
<p>₹1,099</p>
<div class="stars">★★★★★</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1586985289906-406988974504">
<h3>Vanilla Buttercream</h3>
<p>₹799</p>
<div class="stars">★★★★☆</div>
</div>

</div>

<div class="section" id="gallery">
<h2>Cake Gallery 🧁</h2>

<div class="card">
<img src="https://images.unsplash.com/photo-1535141192574-5d4897c12636">
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1551024709-8f23befc6f87">
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542826438-bd32f43d626f">
</div>

</div>

<div class="section" id="reviews">
<h2>Customer Reviews 💖</h2>

<p>"Best cake ever! So fresh and beautifully designed." ⭐⭐⭐⭐⭐</p>
<p>"Perfect birthday cake for my son!" ⭐⭐⭐⭐⭐</p>
<p>"Highly recommend Cravings Hut!" ⭐⭐⭐⭐☆</p>

</div>

<div class="section" id="order">
<h2>Place Your Order 📦</h2>

<form>
<input type="text" placeholder="Your Name"><br>
<input type="tel" placeholder="Phone Number"><br>
<input type="text" placeholder="Cake Flavour"><br>
<input type="date"><br>
<textarea placeholder="Special Instructions"></textarea><br>
<button type="submit">Submit Order</button>
</form>

</div>

<div class="section" id="contact">
<h2>Contact Us 📞</h2>
<p>📍 Jalandhar , India</p>
<p>📞 +91 98765 43210</p>
<p>📧 contact@cravingshut.in</p>
<p>Instagram: @cravingshut</p>
</div>

<footer>
© 2026 Cravings Hut | Made with Love 💗
</footer>

</body>
</html>
