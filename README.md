<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ViralNews Indonesia</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:linear-gradient(135deg,#0f172a,#1e293b,#111827);
    color:white;
    min-height:100vh;
}

header{
    padding:30px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:2rem;
    font-weight:700;
    background:linear-gradient(90deg,#00e5ff,#00ff9d);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

nav a{
    color:#ddd;
    text-decoration:none;
    margin-left:25px;
    transition:.3s;
}

nav a:hover{
    color:#00e5ff;
}

.hero{
    padding:50px 8%;
    text-align:center;
}

.hero h1{
    font-size:3.5rem;
    margin-bottom:15px;
}

.hero p{
    color:#cbd5e1;
    max-width:700px;
    margin:auto;
}

.news-grid{
    padding:30px 8% 80px;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:25px;
}

.card{
    background:rgba(255,255,255,0.08);
    backdrop-filter:blur(14px);
    border:1px solid rgba(255,255,255,0.1);
    border-radius:20px;
    overflow:hidden;
    transition:.4s;
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 20px 40px rgba(0,229,255,.2);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.content{
    padding:20px;
}

.tag{
    display:inline-block;
    background:#00e5ff22;
    color:#00e5ff;
    padding:6px 12px;
    border-radius:50px;
    font-size:.8rem;
    margin-bottom:12px;
}

.content h2{
    font-size:1.2rem;
    margin-bottom:10px;
}

.content p{
    color:#cbd5e1;
    line-height:1.7;
    font-size:.95rem;
}

footer{
    text-align:center;
    padding:25px;
    color:#94a3b8;
    border-top:1px solid rgba(255,255,255,.1);
}
</style>
</head>
<body>

<header>
    <div class="logo">ViralNews</div>

    <nav>
        <a href="#">Home</a>
        <a href="#">Trending</a>
        <a href="#">Nasional</a>
        <a href="#">Teknologi</a>
        <a href="#">Lifestyle</a>
    </nav>
</header>

<section class="hero">
    <h1>🔥 Berita Viral Hari Ini</h1>
    <p>
        Update informasi paling ramai dibicarakan netizen Indonesia.
        Ringkasan berita viral, isu nasional, dan topik trending terbaru.
    </p>
</section>

<section class="news-grid">

    <div class="card">
        <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=1200" alt="">
        <div class="content">
            <span class="tag">TRENDING #1</span>
            <h2>Aksi Solidaritas Warga untuk Mahasiswa Jadi Sorotan</h2>
            <p>
                Viral di media sosial, sejumlah warga membeli dagangan UMKM dan
                pedagang kaki lima untuk dibagikan kepada mahasiswa yang sedang
                melakukan aksi demonstrasi. Banyak netizen memuji aksi tersebut
                sebagai bentuk solidaritas dan dukungan terhadap ekonomi kecil.
            </p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?w=1200" alt="">
        <div class="content">
            <span class="tag">EKONOMI</span>
            <h2>Pergerakan Rupiah dan Kondisi Ekonomi Jadi Perbincangan</h2>
            <p>
                Kondisi ekonomi nasional kembali menjadi topik hangat setelah
                berbagai pembahasan mengenai nilai tukar rupiah dan pasar saham
                ramai diperbincangkan publik di berbagai platform digital.
            </p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?w=1200" alt="">
        <div class="content">
            <span class="tag">MEDIA SOSIAL</span>
            <h2>Video Viral TikTok dan X Kuasai Trending Topic</h2>
            <p>
                Berbagai video pendek dan fenomena media sosial kembali mendominasi
                percakapan netizen. Pakar keamanan digital mengingatkan masyarakat
                untuk berhati-hati terhadap tautan palsu yang memanfaatkan tren viral.
            </p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?w=1200" alt="">
        <div class="content">
            <span class="tag">NASIONAL</span>
            <h2>Kasus Hukum dan Korupsi Masih Mendominasi Pemberitaan</h2>
            <p>
                Berbagai perkembangan kasus hukum dan dugaan korupsi terus
                menjadi perhatian publik. Topik ini masuk dalam daftar berita
                yang paling banyak dibaca masyarakat selama beberapa minggu terakhir.
            </p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?w=1200" alt="">
        <div class="content">
            <span class="tag">TEKNOLOGI</span>
            <h2>AI dan Otomatisasi Jadi Topik Populer Tahun Ini</h2>
            <p>
                Kecerdasan buatan semakin banyak digunakan oleh perusahaan,
                kreator konten, hingga pelaku UMKM. Tren AI disebut sebagai
                salah satu teknologi yang paling berpengaruh saat ini.
            </p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b?w=1200" alt="">
        <div class="content">
            <span class="tag">OLAHRAGA</span>
            <h2>Antusiasme Piala Dunia 2026 Ramai di Media Sosial</h2>
            <p>
                Jadwal pertandingan dan berbagai prediksi tim favorit terus
                memenuhi lini masa. Penggemar sepak bola aktif membahas peluang
                negara-negara unggulan menuju babak berikutnya.
            </p>
        </div>
    </div>

</section>

<footer>
    © 2026 ViralNews Indonesia • Desain Modern News Portal
</footer>

</body>
</html>
