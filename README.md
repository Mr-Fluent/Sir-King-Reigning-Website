 <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Estates & Exclusive Cars</title>

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

.rolls img{
width:75%;
margin:auto;
display:block;
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

<nav>
<h1>Elite Estates & Motors</h1>

<ul>
<li>Home</li>
<li>Cars</li>
<li>Real Estate</li>
<li>Contact</li>
</ul>
</nav>

<div class="hero">
<h2>Luxury Cars & Billionaire Homes</h2>
</div>

<section id="cars">

<h2>Exclusive Cars</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1603584173870-7f23fdae1b7a">
<div class="card-content">
<h3>Audi</h3>
<p class="price">$220,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1592853625601-bb9d23da12fc">
<div class="card-content">
<h3>Porsche 911</h3>
<p class="price">$350,000</p>
</div>
</div>

<div class="card rolls">
<img src="https://images.unsplash.com/photo-1631295868223-63265b40d9e4">
<div class="card-content">
<h3>Rolls Royce Ghost</h3>
<p class="price">$450,000</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1626668893632-6f3a4466d22f" alt="Rolls Royce">
<h3>Dodge Hellcat</h3>
<p class="price">$600,000</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1621135802920-133df287f89c">
<div class="card-content">
<h3>Lamborghini Aventador</h3>
<p class="price">$500,000</p>
</div>
</div>

</div>
</section>


<section id="houses">

<h2>Luxury Homes</h2>

<div class="grid">



<div class="card">
<img src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c" alt="New York Penthouse">
<h3>New York City Penthouse</h3>
<p class="price">$8,500,000</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1499793983690-e29da59ef1c2">
<div class="card-content">
<h3>Beach Resort</h3>
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
<img src="https://images.unsplash.com/photo-1600607688969-a5bfcd646154" alt="Modern House with Garage">
<h3>Modern House with Large Garage</h3>
<p class="price">$2,900,000</p>
</div>

</div>

</section>

<footer>
© 2026 Luxury Estates & Cars
</footer>

</body>
</html>
