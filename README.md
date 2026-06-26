<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hardcore Gym</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#111;
color:white;
}

header{
background:#000;
padding:20px;
text-align:center;
}

header h1{
color:red;
font-size:40px;
}

.hero{
background:url("images.jpeg") center/cover;
height:90vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
}

.overlay{
background:rgba(0,0,0,.6);
width:100%;
height:100%;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
padding:20px;
}

.hero h2{
font-size:55px;
}

.hero p{
margin-top:15px;
font-size:22px;
}

.btn{
margin-top:30px;
padding:15px 35px;
background:red;
color:white;
text-decoration:none;
border-radius:8px;
font-size:22px;
}

section{
padding:50px 20px;
text-align:center;
}

h2{
color:red;
margin-bottom:20px;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

.card{
background:#222;
padding:20px;
border-radius:10px;
width:250px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:15px;
}

.gallery img{
width:100%;
border-radius:10px;
}

footer{
background:black;
padding:30px;
text-align:center;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
padding:15px 20px;
border-radius:50px;
color:white;
text-decoration:none;
font-weight:bold;
}
</style>

</head>

<body>

<header>
<h1>HARDCORE GYM</h1>
</header>

<div class="hero">
<div class="overlay">
<h2>BUILD MUSCLE</h2>
<h2>BUILD POWER</h2>

<p>Bhim Nagar, Rabale, Navi Mumbai - 400701</p>

<a class="btn" href="tel:8454087460">Join Now</a>

</div>
</div>

<section>

<h2>About Us</h2>

<p>

Hardcore Gym provides modern equipment, experienced trainers, cardio, strength training and the best fitness environment.

</p>

</section>

<section>

<h2>Membership Plans</h2>

<div class="cards">

<div class="card">
<h3>Basic</h3>
<h1>₹500</h1>
<p>Gym Access</p>
</div>

<div class="card">
<h3>Standard</h3>
<h1>₹800</h1>
<p>Cardio + Strength</p>
</div>

<div class="card">
<h3>Premium</h3>
<h1>₹1200</h1>
<p>Trainer Support</p>
</div>

</div>

</section>

<section>

<h2>Gallery</h2>

<div class="gallery">

<img src="images.jpeg">

<img src="images (1).jpeg">

<img src="images (2).jpeg">

<img src="images (3).jpeg">

</div>

</section>

<section>

<h2>Contact Us</h2>

<p>

📍 Bhim Nagar, Rabale, Navi Mumbai - 400701

</p>

<br>

<p>

📞 8454087460

</p>

</section>

<footer>

<h2>Hardcore Gym</h2>

<p>Build Strength • Build Confidence</p>

</footer>

<a class="whatsapp" href="https://wa.me/918454087460">

WhatsApp

</a>

</body>

</html>
