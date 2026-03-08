<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Estates & Cars</title>

<style>

body{
font-family: Arial, sans-serif;
margin:0;
background:#111;
color:white;
}

header{
background:black;
padding:20px;
text-align:center;
font-size:28px;
font-weight:bold;
letter-spacing:2px;
}

nav{
text-align:center;
background:#1c1c1c;
padding:10px;
}

nav a{
color:white;
margin:0 15px;
text-decoration:none;
font-weight:bold;
}

section{
padding:40px;
}

h2{
text-align:center;
margin-bottom:30px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#1b1b1b;
border-radius:10px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,0.5);
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card-content{
padding:15px;
text-align:center;
}

.price{
color:#00ffae;
font-size:18px;
margin-top:8px;
}

footer{
background:black;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<header>
Luxury Estates & Exclusive Cars
</header>

<nav>
<a href="#cars">Exclusive Cars</a>
<a href="#houses">Luxury Homes</a>
</nav>


<section id="cars">

<h2>Exclusive Cars</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1621135802920-133df287f89c">
<div class="card-content">
<h3>Lamborghini Aventador</h3>
<p class="price">$500,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1619767886558-efdc259cde1a">
<div class="card-content">
<h3>Aston Martin</h3>
<p class="price">$220,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1592198084033-aade902d1aae">
<div class="card-content">
<h3>Ferrari</h3>
<p class="price">$350,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1631295868223-63265b40d9e4">
<div class="card-content">
<h3>Rolls Royce</h3>
<p class="price">$450,000</p>
</div>
</div>

</div>
</section>



<section id="houses">

<h2>Luxury Homes</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1501183638710-841dd1904471">
<div class="card-content">
<h3>NYC Penthouse</h3>
<p class="price">$8,500,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1505691938895-1758d7feb511">
<div class="card-content">
<h3>Beach House with Volleyball Court</h3>
<p class="price">$3,200,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c">
<div class="card-content">
<h3>Modern House with Basketball Court</h3>
<p class="price">$4,100,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1564013799919-ab600027ffc6">
<div class="card-content">
<h3>Modern House with Big Garage</h3>
<p class="price">$2,800,000</p>
</div>
</div>

</div>

</section>


<footer>
© 2026 Luxury Estates & Cars
</footer>

</body>
</html>
