<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SDN TANGERANG 2 - Website Resmi</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial, sans-serif;}

body{line-height:1.6;background:#f1f5f9;}

header{
    background:#0f3c88;
    color:white;
    padding:25px;
    text-align:center;
}

header h1{font-size:28px;}

nav{
    background:#0a2c63;
    padding:12px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
    font-weight:bold;
}

nav a:hover{color:#38bdf8;}

.hero{
    background:linear-gradient(to right,#2563eb,#1e3a8a);
    color:white;
    padding:100px 20px;
    text-align:center;
}

.hero h2{font-size:32px;margin-bottom:15px;}

section{
    padding:60px 20px;
    text-align:center;
}

.container{
    max-width:1000px;
    margin:auto;
}

.card{
    background:white;
    padding:30px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

.galeri{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
}

.galeri img{
    width:100%;
    border-radius:10px;
}

footer{
    background:#0a2c63;
    color:white;
    padding:20px;
    text-align:center;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
    <h1>SDN TANGERANG 2</h1>
    <p>Kota Tangerang</p>
</header>

<nav>
    <a href="#beranda">Beranda</a>
    <a href="#profil">Profil</a>
    <a href="#visi">Visi Misi</a>
    <a href="#galeri">Galeri</a>
    <a href="#kontak">Kontak</a>
</nav>

<section class="hero" id="beranda">
    <h2>Selamat Datang di Website Resmi SDN TANGERANG 2</h2>
    <p>Sekolah Dasar Negeri unggul dalam prestasi dan berkarakter.</p>
</section>

<section id="profil">
<div class="container">
<div class="card">
<h2>Profil Sekolah</h2>
<p>
SDN Tangerang 2 merupakan sekolah dasar negeri di Kota Tangerang
yang berkomitmen memberikan pendidikan berkualitas,
membentuk karakter siswa, serta menciptakan generasi cerdas dan berakhlak mulia.
</p>
</div>
</div>
</section>

<section id="visi">
<div class="container">
<div class="card">
<h2>Visi</h2>
<p>Terwujudnya peserta didik yang cerdas, berkarakter, dan berprestasi.</p>
<br>
<h2>Misi</h2>
<p>
- Menyelenggarakan pembelajaran yang aktif dan kreatif<br>
- Menanamkan nilai karakter dan disiplin<br>
- Mengembangkan potensi akademik dan non-akademik siswa
</p>
</div>
</div>
</section>

<section id="galeri">
<div class="container">
<h2>Galeri Kegiatan</h2>
<br>
<div class="galeri">
<img src="https://source.unsplash.com/400x300/?school" alt="Kegiatan Sekolah">
<img src="https://source.unsplash.com/400x300/?classroom" alt="Kelas">
<img src="https://source.unsplash.com/400x300/?students" alt="Siswa">
</div>
</div>
</section>

<section id="kontak">
<div class="container">
<div class="card">
<h2>Kontak Kami</h2>
<p>Email: sdntangerang2@gmail.com</p>
<p>Telepon: 021-55783910</p>
<p>Alamat: Jl. A. Damyati No 39 Sukarasa, Kota Tangerang</p>
</div>
</div>
</section>

<footer>
<p>&copy; 2026 SDN TANGERANG 2 | Kota Tangerang</p>
</footer>

</body>
</html>
