# rono-hill-restaurant
Professional restaurant website for Rono Hill Restaurant in Doimukh, Arunachal Pradesh.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Rono Hill Restaurant | Family Restaurant in Doimukh</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,Arial,sans-serif;
scroll-behavior:smooth;
}

body{
line-height:1.6;
color:#333;
}

/* NAVBAR */

header{
background:#111;
color:white;
padding:15px 30px;
position:sticky;
top:0;
z-index:999;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
}

nav h1{
font-size:24px;
}

nav ul{
list-style:none;
display:flex;
}

nav ul li{
margin-left:25px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:500;
}

nav ul li a:hover{
color:#f4b400;
}

/* HERO */

.hero{
height:85vh;
background:url("https://images.unsplash.com/photo-1555992336-03a23c7b20ee") center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
}

.hero h2{
font-size:50px;
}

.hero p{
font-size:20px;
margin:15px 0;
}

.btn{
background:#f4b400;
color:black;
padding:12px 28px;
border-radius:5px;
text-decoration:none;
font-weight:bold;
}

/* SECTION */

section{
padding:70px 20px;
max-width:1100px;
margin:auto;
}

section h2{
text-align:center;
margin-bottom:40px;
font-size:32px;
}

/* ABOUT */

.about{
text-align:center;
max-width:800px;
margin:auto;
}

/* MENU */

.menu{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.menu-item{
background:#f9f9f9;
padding:20px;
border-radius:10px;
box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.menu-item h3{
display:flex;
justify-content:space-between;
margin-bottom:10px;
}

/* GALLERY */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:10px;
}

.gallery img{
width:100%;
border-radius:8px;
}

/* REVIEWS */

.reviews{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.review{
background:#f5f5f5;
padding:20px;
border-radius:10px;
}

/* CONTACT */

.contact{
display:grid;
grid-template-columns:1fr 1fr;
gap:30px;
}

.contact form{
display:grid;
gap:15px;
}

input,textarea{
padding:10px;
border:1px solid #ccc;
border-radius:5px;
}

button{
background:#111;
color:white;
padding:12px;
border:none;
cursor:pointer;
}

iframe{
width:100%;
height:300px;
border:0;
}

/* WHATSAPP */

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 18px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

/* FOOTER */

footer{
background:#111;
color:white;
text-align:center;
padding:25px;
margin-top:40px;
}

@media(max-width:768px){

.contact{
grid-template-columns:1fr;
}

.hero h2{
font-size:36px;
}

}

</style>
</head>

<body>

<header>
<nav>
<h1>Rono Hill Restaurant</h1>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#menu">Menu</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#reviews">Reviews</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<!-- HERO -->

<section class="hero" id="home">
<div>
<h2>Welcome to Rono Hill Restaurant</h2>
<p>Best Family Dining in Doimukh</p>
<a class="btn" href="#menu">View Menu</a>
</div>
</section>

<!-- ABOUT -->

<section id="about">

<h2>About Us</h2>

<p class="about">
Located in the heart of Doimukh, Rono Hill Restaurant offers
delicious meals, a comfortable family atmosphere, and friendly
service. We specialize in local flavors, popular Indian dishes,
and quick snacks for travelers and families.
</p>

</section>

<!-- MENU -->

<section id="menu">

<h2>Popular Menu</h2>

<div class="menu">

<div class="menu-item">
<h3>Fried Rice <span>₹120</span></h3>
<p>Delicious fried rice with fresh vegetables.</p>
</div>

<div class="menu-item">
<h3>Chicken Curry <span>₹180</span></h3>
<p>Traditional spicy chicken curry with rice.</p>
</div>

<div class="menu-item">
<h3>Veg Momos <span>₹90</span></h3>
<p>Steamed dumplings served with spicy sauce.</p>
</div>

<div class="menu-item">
<h3>Chowmein <span>₹110</span></h3>
<p>Popular stir-fried noodles with vegetables.</p>
</div>

</div>

</section>

<!-- GALLERY -->

<section id="gallery">

<h2>Food Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">

<img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1">

<img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c">

<img src="https://images.unsplash.com/photo-1604908176997-431e6e3e04b2">

</div>

</section>

<!-- REVIEWS -->

<section id="reviews">

<h2>Customer Reviews</h2>

<div class="reviews">

<div class="review">
<p>"Great food and friendly service. Perfect place for family dinner."</p>
<b>★★★★★</b>
</div>

<div class="review">
<p>"Affordable prices and tasty local dishes."</p>
<b>★★★★☆</b>
</div>

<div class="review">
<p>"Nice location and good atmosphere."</p>
<b>★★★★☆</b>
</div>

</div>

</section>

<!-- CONTACT -->

<section id="contact">

<h2>Contact & Reservation</h2>

<div class="contact">

<form>

<input type="text" placeholder="Your Name" required>

<input type="tel" placeholder="Phone Number" required>

<textarea placeholder="Reservation or message"></textarea>

<button>Send Request</button>

</form>

<div>

<iframe src="https://maps.google.com/maps?q=Rono%20Doimukh%20Arunachal%20Pradesh&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>

</div>

</div>

</section>

<footer>

<p>© 2026 Rono Hill Restaurant – Doimukh, Arunachal Pradesh</p>

<p>
Follow us:
Facebook | Instagram | WhatsApp
</p>

</footer>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX">
WhatsApp Order
</a>

</body>
</html>
