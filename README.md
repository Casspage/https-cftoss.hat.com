<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CF Toss Coffee</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#faf7f2;
color:#333;
}

/* HERO */
header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
url('https://images.unsplash.com/photo-1509042239860-f550ce710b93?q=80&w=1600');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

.hero h1{
font-size:70px;
}

.hero p{
font-size:22px;
margin-top:10px;
}

.btn{
display:inline-block;
margin-top:25px;
padding:14px 28px;
background:#c58b45;
color:white;
text-decoration:none;
border-radius:40px;
transition:.3s;
}

.btn:hover{
background:#9e6b31;
transform:translateY(-3px);
}

/* SECTION */
section{
max-width:1100px;
margin:auto;
padding:80px 20px;
}

.title{
text-align:center;
font-size:38px;
margin-bottom:40px;
color:#4a2f1b;
}

/* ABOUT */
.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,.2);
}

/* MENU */
.menu{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:18px;
box-shadow:0 5px 20px rgba(0,0,0,.1);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.price{
color:#c58b45;
font-weight:bold;
margin-top:10px;
font-size:20px;
}

/* CONTACT */
.contact{
background:#3b2415;
color:white;
padding:50px;
border-radius:20px;
text-align:center;
}

.contact p{
margin:10px 0;
font-size:18px;
}

/* MAP */
.map{
margin-top:20px;
border-radius:15px;
overflow:hidden;
box-shadow:0 10px 20px rgba(0,0,0,.2);
}

/* FOOTER */
footer{
background:#2b1a10;
color:white;
text-align:center;
padding:20px;
margin-top:50px;
}

/* MOBILE */
@media(max-width:768px){
.hero h1{font-size:45px;}
.about{grid-template-columns:1fr;}
}

</style>
</head>

<body>

<header>
<div class="hero">
<h1>☕ CF Toss</h1>
<p>Cà Phê Phin Đậm Đà - Không Gian Thư Giãn</p>
<a href="#contact" class="btn">Đến Quán Ngay</a>
</div>
</header>

<section>
<h2 class="title">Về CF Toss</h2>

<div class="about">

<img src="https://images.unsplash.com/photo-1498804103079-a6351b050096?q=80&w=1200">

<div>
<p>
CF Toss là quán cà phê phin truyền thống Việt Nam,
mang đến hương vị đậm đà và không gian hiện đại, ấm cúng.
</p>

<br>

<p>
Chúng tôi phục vụ cà phê rang mộc, pha phin chuẩn vị,
phù hợp học tập, làm việc và thư giãn.
</p>

</div>

</div>
</section>

<section>
<h2 class="title">Menu</h2>

<div class="menu">

<div class="card">
<h3>Cà Phê Phin Đen</h3>
<p>Đậm, nguyên chất</p>
<div class="price">29.000đ</div>
</div>

<div class="card">
<h3>Cà Phê Sữa</h3>
<p>Ngọt béo truyền thống</p>
<div class="price">35.000đ</div>
</div>

<div class="card">
<h3>Bạc Xỉu</h3>
<p>Nhẹ nhàng, dễ uống</p>
<div class="price">39.000đ</div>
</div>

<div class="card">
<h3>Cold Brew</h3>
<p>Mát lạnh hiện đại</p>
<div class="price">45.000đ</div>
</div>

</div>
</section>

<section id="contact">
<h2 class="title">Liên Hệ</h2>

<div class="contact">

<p>📍 144 Xuân Thủy - Cầu Giấy - Hà Nội</p>
<p>📞 0988 876 678</p>
<p>🕒 07:00 - 22:00</p>

<br>

<a class="btn" href="tel:0988876678">Gọi Ngay</a>

<!-- GOOGLE MAP -->
<div class="map">
<iframe
src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3723.876...Xuân Thủy Hà Nội"
width="100%"
height="300"
style="border:0;"
allowfullscreen=""
loading="lazy">
</iframe>
</div>

</div>
</section>

<footer>
© 2026 CF Toss Coffee
</footer>

</body>
</html>
