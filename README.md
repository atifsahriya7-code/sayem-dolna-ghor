<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sayem Dolna Ghor</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f8f9fa;
}

header{
background:linear-gradient(135deg,#0066ff,#ff7a00);
padding:20px;
color:white;
text-align:center;
}

.logo{
font-size:38px;
font-weight:700;
}

.tagline{
margin-top:10px;
font-size:18px;
}

nav{
background:white;
padding:15px;
text-align:center;
box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

nav a{
text-decoration:none;
margin:0 15px;
color:#0066ff;
font-weight:600;
}

.hero{
padding:80px 20px;
text-align:center;
background:linear-gradient(rgba(0,102,255,.85),rgba(255,122,0,.85)),
url('https://images.unsplash.com/photo-1505693416388-ac5ce068fe85');
background-size:cover;
background-position:center;
color:white;
}

.hero h1{
font-size:50px;
}

.hero p{
margin-top:20px;
font-size:20px;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 25px;
background:white;
color:#0066ff;
font-weight:bold;
border-radius:30px;
text-decoration:none;
}

.section{
padding:60px 20px;
max-width:1200px;
margin:auto;
}

.section-title{
text-align:center;
font-size:35px;
margin-bottom:40px;
color:#0066ff;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 5px 20px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:250px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.price{
color:#ff7a00;
font-size:24px;
font-weight:bold;
margin-top:10px;
}

.about{
background:white;
border-radius:15px;
padding:30px;
box-shadow:0 5px 20px rgba(0,0,0,0.1);
}

.payment{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:15px;
}

.pay-box{
background:white;
padding:20px;
text-align:center;
border-radius:12px;
font-weight:600;
box-shadow:0 3px 10px rgba(0,0,0,0.1);
}

.contact{
text-align:center;
}

.contact p{
margin:10px 0;
}

footer{
background:#111;
color:white;
padding:25px;
text-align:center;
}

.language{
position:fixed;
top:20px;
right:20px;
background:white;
padding:8px;
border-radius:10px;
}

</style>
</head>

<body>

<div class="language">
<select onchange="changeLanguage(this.value)">
<option value="en">English</option>
<option value="bn">বাংলা</option>
</select>
</div>

<header>
<div class="logo">Sayem Dolna Ghor</div>
<div class="tagline" id="tagline">
Premium Swing & Furniture Shop
</div>
</header>

<nav>
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#payment">Payment</a>
<a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
<h1 id="heroTitle">Stylish Dolna Collection</h1>
<p id="heroText">
Best Quality Swing Products in Bangladesh
</p>
<a href="#products" class="btn">View Products</a>
</section>

<section class="section" id="products">

<h2 class="section-title">Featured Products</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
<div class="card-content">
<h3>Wooden Luxury Dolna</h3>
<p>Premium Quality Handmade</p>
<div class="price">৳ 15,000</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1484154218962-a197022b5858">
<div class="card-content">
<h3>Modern Hanging Swing</h3>
<p>Indoor & Outdoor Use</p>
<div class="price">৳ 12,000</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
<div class="card-content">
<h3>Family Size Dolna</h3>
<p>Heavy Duty Steel Frame</p>
<div class="price">৳ 20,000</div>
</div>
</div>

</div>

</section>

<section class="section" id="about">

<h2 class="section-title">About Us</h2>

<div class="about">

<p>
Sayem Dolna Ghor বাংলাদেশের অন্যতম বিশ্বস্ত দোলনা ও ফার্নিচার বিক্রেতা প্রতিষ্ঠান।
</p>

<br>

<p>
We provide premium quality swings and furniture across Bangladesh.
</p>

</div>

</section>

<section class="section" id="payment">

<h2 class="section-title">Payment Methods</h2>

<div class="payment">

<div class="pay-box">bKash</div>
<div class="pay-box">Nagad</div>
<div class="pay-box">Rocket</div>
<div class="pay-box">Upay</div>
<div class="pay-box">Visa Card</div>
<div class="pay-box">Master Card</div>
<div class="pay-box">American Express</div>
<div class="pay-box">Bank Transfer</div>

</div>

</section>

<section class="section contact" id="contact">

<h2 class="section-title">Contact</h2>

<p>📞 +8801XXXXXXXXX</p>
<p>📧 info@sayemdolnaghor.com</p>
<p>📍 Bangladesh</p>

</section>

<footer>

© 2026 Sayem Dolna Ghor | All Rights Reserved

</footer>

<script>

function changeLanguage(lang){

if(lang==="bn"){

document.getElementById("heroTitle").innerHTML="স্টাইলিশ দোলনা কালেকশন";

document.getElementById("heroText").innerHTML=
"বাংলাদেশের সেরা মানের দোলনা সংগ্রহ";

document.getElementById("tagline").innerHTML=
"প্রিমিয়াম দোলনা ও ফার্নিচার শপ";

}else{

document.getElementById("heroTitle").innerHTML=
"Stylish Dolna Collection";

document.getElementById("heroText").innerHTML=
"Best Quality Swing Products in Bangladesh";

document.getElementById("tagline").innerHTML=
"Premium Swing & Furniture Shop";

}

}

</script>

</body>
</html>