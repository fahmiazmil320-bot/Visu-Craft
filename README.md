<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Visu Craft | Premium Graphic Design</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">

<style>
* {
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins', sans-serif;
}

body {
    background: linear-gradient(135deg,#0f172a,#020617);
    color:white;
    scroll-behavior:smooth;
}

header {
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
}

header h1 {
    font-size:60px;
    background:linear-gradient(90deg,#38bdf8,#818cf8);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

header p {
    max-width:700px;
    margin-top:20px;
    color:#cbd5e1;
}

.btn {
    margin-top:25px;
    padding:12px 25px;
    background:linear-gradient(90deg,#38bdf8,#6366f1);
    border:none;
    border-radius:30px;
    color:white;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.btn:hover {
    transform:scale(1.1);
}

section {
    padding:80px 10%;
}

h2 {
    text-align:center;
    font-size:35px;
    margin-bottom:40px;
    background:linear-gradient(90deg,#38bdf8,#818cf8);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.about p {
    max-width:800px;
    margin:auto;
    text-align:center;
    color:#cbd5e1;
}

.skills, .services {
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.card {
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(15px);
    padding:30px;
    border-radius:20px;
    text-align:center;
    transition:0.3s;
}

.card:hover {
    transform:translateY(-10px);
    background:rgba(255,255,255,0.1);
}

.gallery {
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.gallery img {
    width:100%;
    border-radius:20px;
    transition:0.4s;
}

.gallery img:hover {
    transform:scale(1.05);
}

.contact-box {
    text-align:center;
    background:rgba(255,255,255,0.05);
    padding:40px;
    border-radius:20px;
}

footer {
    text-align:center;
    padding:20px;
    background:#020617;
    color:#94a3b8;
}

.whatsapp {
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    padding:15px 18px;
    border-radius:50%;
    color:white;
    font-size:22px;
    text-decoration:none;
    box-shadow:0 0 20px rgba(0,0,0,0.5);
}
</style>
</head>
<body>

<header>
    <h1>Visu Craft</h1>
    <p>Creative Visual Designer by FAHMI AZMIL ATHAILLAH  
    Mengubah ide menjadi visual yang powerful, modern, dan berkelas.</p>
    <a href="#contact" class="btn">Hire Me</a>
</header>

<section class="about">
    <h2>Tentang Saya</h2>
    <p>
    Saya FAHMI AZMIL ATHAILLAH, pendiri Visu Craft.  
    Saya memilih menjadi desainer grafis karena saya percaya bahwa visual memiliki kekuatan 
    untuk menyampaikan pesan lebih kuat daripada kata-kata.  
    Melalui desain, saya membantu brand tampil profesional, menarik perhatian, 
    dan meningkatkan nilai bisnis mereka.
    </p>
</section>

<section>
    <h2>Software Skills</h2>
    <div class="skills">
        <div class="card">Canva</div>
        <div class="card">Affinity Designer</div>
        <div class="card">PixelLab</div>
        <div class="card">CapCut</div>
    </div>
</section>

<section>
    <h2>Layanan Desain</h2>
    <div class="services">
        <div class="card">
            <h3>Desain Poster</h3>
            <p>Poster Event, Poster Promosi, Poster Produk, Poster Digital Marketing</p>
        </div>
        <div class="card">
            <h3>Desain Logo</h3>
            <p>Logo UMKM, Logo Brand, Logo Modern & Minimalis</p>
        </div>
        <div class="card">
            <h3>Konten Sosial Media</h3>
            <p>Feed Instagram, Banner, Story, Reels Cover</p>
        </div>
    </div>
</section>

<section>
    <h2>Portofolio</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0" alt="">
        <img src="https://images.unsplash.com/photo-1492724441997-5dc865305da7" alt="">
        <img src="https://images.unsplash.com/photo-1517842645767-c639042777db" alt="">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="">
    </div>
</section>

<section id="contact">
    <h2>Hubungi Saya</h2>
    <div class="contact-box">
        <p><strong>FAHMI AZMIL ATHAILLAH</strong></p>
        <p>Brand: Visu Craft</p>
        <p>WhatsApp: +62 877-1768-2868</p>
        <br>
        <a href="https://wa.me/6287717682868" class="btn" target="_blank">Chat WhatsApp</a>
        <br><br>
        <a href="https://lynk.id/hyperdigi" class="btn" target="_blank">Toko Produk Digital</a>
    </div>
</section>

<footer>
© 2026 Visu Craft — Premium Graphic Design Service
</footer>

<a href="https://wa.me/6287717682868" class="whatsapp" target="_blank">💬</a>

</body>
</html>
