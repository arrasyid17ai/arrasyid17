
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


  }

  .hero-content p {
    font-size: 16px;
  }
}
