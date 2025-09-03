
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LATIHAN WEB ARRASYID</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- ===== Navbar ===== -->
  <header class="navbar">
    <div class="logo">ALAMAKSHOP</div>
    <nav class="nav">
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#produk">Produk</a></li>
        <li><a href="#tentang">Tentang</a></li>
        <li><a href="#kontak">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <!-- ===== Hero Section ===== -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h1>Selamat Datang di ALAMAKSHOP</h1>
      <p>Temukan produk terbaik kami dengan kualitas tinggi dan harga terjangkau.</p>
      <a href="#produk" class="btn">Lihat Produk</a>
    </div>
  </section>

  <!-- ===== Produk Section ===== -->
  <section id="produk" class="section">
    <h2>Produk Kami</h2>
    <div class="produk-grid">

      <div class="produk-card">
        <img src="download (2).jpg" alt="Produk 1">
        <h3>Produk 1</h3>
        <p>Produk berkualitas tinggi untuk kebutuhan sehari-hari Anda.</p>
        <button>Beli Sekarang</button>
      </div>

      <div class="produk-card">
        <img src="download (3).jpg" alt="Produk 2">
        <h3>Produk 2</h3>
        <p>Produk populer dengan desain modern dan fungsional.</p>
        <button>Beli Sekarang</button>
      </div>

      <div class="produk-card">
        <img src="download.jpg" alt="Produk 3">
        <h3>Produk 3</h3>
        <p>Produk inovatif untuk mendukung gaya hidup Anda.</p>
        <button>Beli Sekarang</button>
      </div>

      <div class="produk-card">
        <img src="𝔂𝔀𝓵𝓸𝔀.jpg" alt="Produk 4">
        <h3>Produk 4</h3>
        <p>Produk terpercaya dengan banyak pilihan warna dan model.</p>
        <button>Beli Sekarang</button>
      </div>

    </div>
  </section>

  <!-- ===== Tentang Section ===== -->
  <section id="tentang" class="section">
    <h2>Tentang Kami</h2>
    <p style="text-align:center; max-width:700px; margin:auto;">
      ALAMAKSHOP adalah penyedia produk berkualitas yang mengutamakan kepuasan pelanggan.
      Kami hadir dengan berbagai inovasi untuk memberikan pengalaman belanja yang lebih baik.
    </p>
  </section>

  <!-- ===== Kontak Section ===== -->
  <section id="kontak" class="section kontak">
    <h2>Hubungi Kami</h2>
    <div class="kontak-container">
      <form class="kontak-form">
        <input type="text" placeholder="Nama Anda" required>
        <input type="email" placeholder="Email Anda" required>
        <textarea placeholder="Pesan Anda" rows="5" required></textarea>
        <button type="submit">Kirim Pesan</button>
      </form>
      <div class="map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3952.074566984015!2d110.36948937402183!3d-7.881140292127711!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e7a578c7bbab3e1%3A0x5030bfbcaf7c1c0!2sYogyakarta!5e0!3m2!1sid!2sid!4v1691030497784!5m2!1sid!2sid"
          width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </div>
    </div>
  </section>

  <!-- ===== Footer ===== -->
  <footer class="footer">
    <p>&copy; 2025 ALAMAKSHOP. Semua Hak Dilindungi.</p>
  </footer>

</body>
</html>


/* ===== Reset dasar ===== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background: #f9fafb;
  color: #111827;
}

/* ===== Navbar ===== */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #0f172a;
  color: #fff;
  padding: 15px 20px;
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo {
  font-size: 20px;
  font-weight: bold;
}

.nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav a {
  text-decoration: none;
  color: #e5e7eb;
  padding: 8px 12px;
  border-radius: 8px;
  transition: 0.3s;
}

.nav a:hover {
  background: rgba(255, 255, 255, 0.2);
}

/* ===== Hero Section ===== */
.hero {
  background: url('https://images.unsplash.com/photo-1522206024047-9c9254216759?auto=format&fit=crop&w=1600&q=80') no-repeat center center/cover;
  height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  text-align: center;
  padding: 0 20px;
}

.hero-content h1 {
  font-size: 42px;
  margin-bottom: 15px;
}

.hero-content p {
  font-size: 18px;
  margin-bottom: 20px;
}

.btn {
  background: #06b6d4;
  color: white;
  padding: 12px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background: #0891b2;
}

/* ===== Section umum ===== */
.section {
  padding: 60px 20px;
  max-width: 1200px;
  margin: auto;
}

.section h2 {
  text-align: center;
  font-size: 28px;
  margin-bottom: 30px;
  color: #0f172a;
}

/* ===== Produk Grid ===== */
.produk-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
}

.produk-card {
  background: #fff;
  border-radius: 12px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.produk-card:hover {
  transform: translateY(-6px);
}

.produk-card img {
  max-width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

.produk-card h3 {
  margin-bottom: 10px;
  color: #06b6d4;
}

.produk-card p {
  font-size: 14px;
  margin-bottom: 15px;
  color: #374151;
}

.produk-card button {
  background: #06b6d4;
  color: white;
  border: none;
  padding: 10px 16px;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.produk-card button:hover {
  background: #0891b2;
}

/* ===== Kontak Section ===== */
.kontak-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  align-items: start;
}

.kontak-form {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.kontak-form input,
.kontak-form textarea {
  padding: 12px;
  border: 1px solid #d1d5db;
  border-radius: 8px;
  font-size: 14px;
}

.kontak-form button {
  background: #06b6d4;
  color: white;
  border: none;
  padding: 12px;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}

.kontak-form button:hover {
  background: #0891b2;
}

.map {
  width: 100%;
  height: 350px;
  border-radius: 12px;
  overflow: hidden;
}

/* ===== Footer ===== */
.footer {
  background: #0f172a;
  color: #e5e7eb;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}

/* ===== Responsif ===== */
@media (max-width: 768px) {
  .kontak-container {
    grid-template-columns: 1fr;
  }

  .hero-content h1 {
    font-size: 28px;
  }

  .hero-content p {
    font-size: 16px;
  }
}
