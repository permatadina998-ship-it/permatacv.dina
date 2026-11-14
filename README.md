<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV - Teknik Komputer dan Jaringan</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
    scroll-behavior: smooth;
}

body {
    background: #0b1120;
    color: white;
}

header {
    background: #111c32;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 10;
}

.logo {
    color: #38bdf8;
    font-size: 25px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
}

nav a:hover {
    color: #38bdf8;
}

section {
    padding: 75px 10%;
}

.hero {
    min-height: 85vh;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
}

.hero h1 {
    font-size: 45px;
    margin-bottom: 15px;
}

.hero h1 span {
    color: #38bdf8;
}

.hero p {
    color: #cbd5e1;
    line-height: 1.8;
}

.profile {
    width: 250px;
    height: 250px;
    border-radius: 50%;
    border: 5px solid #38bdf8;
    object-fit: cover;
    background: #1e293b;
}

.btn {
    display: inline-block;
    background: #0284c7;
    color: white;
    padding: 12px 25px;
    border-radius: 8px;
    text-decoration: none;
    margin-top: 20px;
    border: none;
    cursor: pointer;
}

.btn:hover {
    background: #0369a1;
}

h2 {
    color: #38bdf8;
    font-size: 30px;
    margin-bottom: 25px;
    text-align: center;
}

.card {
    background: #17243b;
    padding: 25px;
    border-radius: 15px;
    margin-bottom: 20px;
    border: 1px solid #263b59;
}

.card p {
    color: #cbd5e1;
    line-height: 1.8;
}

.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
}

.skill {
    background: #17243b;
    padding: 20px;
    text-align: center;
    border-radius: 10px;
    border: 1px solid #38bdf8;
    transition: 0.3s;
}

.skill:hover {
    transform: translateY(-5px);
    background: #075985;
}

footer {
    background: #111c32;
    text-align: center;
    padding: 25px;
    color: #94a3b8;
}

@media(max-width: 700px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav a {
        margin: 5px;
        font-size: 13px;
    }

    .hero {
        flex-direction: column-reverse;
        text-align: center;
        padding-top: 50px;
    }

    .hero h1 {
        font-size: 32px;
    }
}

@media print {
    header, .btn {
        display: none;
    }

    body {
        background: white;
        color: black;
    }

    .card, .skill {
        background: white;
        color: black;
        border: 1px solid #aaa;
    }

    .card p {
        color: black;
    }

    section {
        padding: 25px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">MY CV.</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Profil</a>
        <a href="#pendidikan">Pendidikan</a>
        <a href="#skill">Keahlian</a>
        <a href="#kontak">Kontak</a>
    </nav>
</header>

<section class="hero" id="home">
    <div>
        <h1>Halo, Saya <span>NAMA KAMU</span></h1>
        <h3>Teknik Komputer dan Jaringan</h3>
        <p>
            Saya merupakan siswa jurusan TKJ yang memiliki
            minat dalam bidang komputer, jaringan internet,
            instalasi jaringan, dan teknologi informasi.
        </p>
        <button class="btn" onclick="window.print()">
            Download / Cetak CV
        </button>
    </div>

    <img src="foto.jpg" class="profile" alt="Foto Profil">
</section>

<section id="about">
    <h2>Tentang Saya</h2>
    <div class="card">
        <p>
            Saya adalah pribadi yang disiplin, bertanggung jawab,
            mampu bekerja sama dalam tim, dan memiliki semangat
            belajar yang tinggi. Saya memiliki ketertarikan
            dalam dunia teknologi khususnya komputer dan jaringan.
        </p>
        <br>
        <p><b>Nama:</b> Nama Lengkap</p>
        <p><b>Tempat, Tanggal Lahir:</b> Kota, Tanggal Lahir</p>
        <p><b>Alamat:</b> Alamat Lengkap</p>
        <p><b>Email:</b> email@gmail.com</p>
        <p><b>No. HP:</b> 08xxxxxxxxxx</p>
    </div>
</section>

<section id="pendidikan">
    <h2>Riwayat Pendidikan</h2>

    <div class="card">
        <h3>SMK - Teknik Komputer dan Jaringan</h3>
        <p>2024 - Sekarang</p>
        <p>Mempelajari komputer, jaringan, server, dan teknologi informasi.</p>
    </div>

    <div class="card">
        <h3>SMP</h3>
        <p>2021 - 2024</p>
        <p>Pendidikan menengah pertama.</p>
    </div>
</section>

<section id="skill">
    <h2>Keahlian TKJ</h2>

    <div class="skills">
        <div class="skill">💻 Hardware Komputer</div>
        <div class="skill">🌐 Instalasi LAN</div>
        <div class="skill">🔌 Crimping Kabel</div>
        <div class="skill">📡 Konfigurasi Mikrotik</div>
        <div class="skill">🖧 Cisco Packet Tracer</div>
        <div class="skill">⚙️ Instalasi Windows</div>
        <div class="skill">🌍 IP Address</div>
        <div class="skill">🛠️ Troubleshooting</div>
    </div>
</section>

<section>
    <h2>Pengalaman</h2>
    <div class="card">
        <h3>Praktik Kerja Lapangan (PKL)</h3>
        <p>Nama Perusahaan / Tempat PKL</p>
        <p>Isi pengalaman kerja, kegiatan, dan tugas selama PKL.</p>
    </div>
</section>

<section>
    <h2>Sertifikat</h2>
    <div class="card">
        <p>• Sertifikat Praktik Jaringan Komputer</p>
        <p>• Sertifikat Pelatihan Mikrotik (jika ada)</p>
        <p>• Sertifikat Kompetensi TKJ (jika ada)</p>
    </div>
</section>

<section id="kontak">
    <h2>Hubungi Saya</h2>
    <div class="card">
        <p>Email: email@gmail.com</p>
        <p>WhatsApp: 08xxxxxxxxxx</p>
        <p>Instagram: @username</p>
    </div>
</section>

<footer>
    <p>© 2026 CV Personal | Teknik Komputer dan Jaringan</p>
    <p>Designed by Nama Kamu</p>
</footer>

</body>
</html>