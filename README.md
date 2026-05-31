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
scroll-behavior:smooth;
}

body{
background:#faf7f2;
color:#333;
}

header{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?q=80&w=1600');
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
margin-bottom:10px;
letter-spacing:2px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:#c58b45;
color:white;
text-decoration:none;
border-radius:50px;
transition:.3s;
}

.btn:hover{
background:#9e6b31;
transform:translateY(-3px);
}

section{
max-width:1200px;
margin:auto;
padding:80px 20px;
}

.title{
text-align:center;
font-size:38px;
margin-bottom:40px;
color:#4a2f1b;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,.15);
}

.about-text p{
font-size:18px;
line-height:1.8;
}

.menu{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:18px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
margin-bottom:10px;
color:#6a3d1f;
}

.price{
font-size:22px;
font-weight:bold;
color:#c58b45;
margin-top:10px;
}

.contact{
background:#4a2f1b;
color:white;
border-radius:25px;
padding:50px;
text-align:center;
}

.contact h2{
margin-bottom:20px;
}

.contact p{
margin:10px 0;
font-size:18px;
}

footer{
background:#2f1d11;
color:white;
text-align:center;
padding:20px;
margin-top:50px;
}

@media(max-width:768px){

.hero h1{
font-size:45px;
}

.about{
grid-template-columns:1fr;
}

}

</style>
</head>
<body>

<header>
<div class="hero">
<h1>☕ CF Toss</h1>
<p>Cà Phê Phin Đậm Đà - Không Gian Thư Giãn</p>
<a href="#contact" class="btn">Liên Hệ Ngay</a>
</div>
</header>

<section>
<h2 class="title">Về CF Toss</h2>

<div class="about">

<img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93?q=80&w=1200" alt="Cafe">

<div class="about-text">
<p>
CF Toss là điểm hẹn dành cho những người yêu cà phê phin truyền thống.
Chúng tôi lựa chọn những hạt cà phê chất lượng, rang mộc và pha bằng phin
để giữ trọn hương vị đậm đà của cà phê Việt Nam.
</p>

<br>

<p>
Không gian ấm cúng, hiện đại cùng đội ngũ phục vụ tận tâm sẽ mang đến cho bạn
những phút giây thư giãn và trải nghiệm đáng nhớ.
</p>

</div>

</div>
</section>

<section>

<h2 class="title">Menu Nổi Bật</h2>

<div class="menu">

<div class="card">
<h3>☕ Cà Phê Phin Đen</h3>
<p>Đậm đà, nguyên bản.</p>
<div class="price">29.000đ</div>
</div>

<div class="card">
<h3>🥛 Cà Phê Sữa Đá</h3>
<p>Hương vị truyền thống Việt Nam.</p>
<div class="price">35.000đ</div>
</div>

<div class="card">
<h3>🍫 Bạc Xỉu</h3>
<p>Ngọt dịu, thơm sữa.</p>
<div class="price">39.000đ</div>
</div>

<div class="card">
<h3>🧋 Cold Brew</h3>
<p>Thanh mát, hiện đại.</p>
<div class="price">45.000đ</div>
</div>

</div>

</section>

<section id="contact">

<div class="contact">

<h2>Liên Hệ CF Toss</h2>

<p>📍 144 Xuân Thủy - Cầu Giấy - Hà Nội</p>

<p>📞 0988 876 678</p>

<p>🕘 Mở cửa: 07:00 - 22:00</p>

<br>

<a href="tel:0988876678" class="btn">Gọi Ngay</a>

</div>

</section>

<footer>
© 2026 CF Toss Coffee - All Rights Reserved
</footer>

</body>
</html> đây là code
