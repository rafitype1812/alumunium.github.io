<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Toko Aluminium & Baut Mur</title>
  <link rel="stylesheet" href="toko2.css" />
</head>
<body>
  <header>
    <div class="logo">
      <img src="image/logo ba.png" alt="Logo Barakah" style="height: 40px;">
      <a href="toko2.html"> Barokah Aluminium</a>
    </div>
    <nav>
      <a href="toko2.html">Beranda</a>
      <a href="halproduk.html">Produk</a>
      <a href="tentang.html">Tentang Kami</a>
      <a href="kontak.html">Kontak</a>
      <a href="keranjang.html" class="keranjang-link">
        🛒 <span id="jumlah-keranjang">0</span>
      </a>
      <a href="signup.html" id="loginNavLink" style="color: white; margin-left: 20px;">Sign up</a>
      <span id="userStatus" style="color: white; margin-left: 20px;"></span>
      <button id="logoutBtn" style="display:none; background-color:#f44336; color:white; border:none; padding: 5px 10px; border-radius:3px; cursor:pointer;">Logout</button>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-slider">
      <div class="slide active" style="background-image: url('image/tukang.png');"></div>
      <div class="slide" style="background-image: url('image/baut.jpg');"></div>
      <div class="slide" style="background-image: url('image/alumunium.png');"></div>

      <button class="slide-btn prev">❮</button>
      <button class="slide-btn next">❯</button>
    </div>
    <div class="hero-content">
      <h1>Solusi Kuat untuk Konstruksi Anda</h1>
      <div class="buttons">
        <a href="#produk" class="btn btn-orange">Lihat Produk</a>
      </div>
    </div>
  </section>

  <section id="produk" class="produk">
    <h2>Kategori Produk</h2>
    <div class="produk-grid">
      <div class="card">
        <a href="alumunium.html">
          <img src="image/alumunium.png" alt="Aluminium Lembaran">
          <p>Alumunium</p>
        </a>
      </div>
      <div class="card">
        <a href="aksesoris.html">
          <img src="image/aksesoris.png" alt="Aluminium Lembaran">
          <p>Aksesoris</p>
        </a>
      </div>
      <div class="card">
        <a href="kaca.html">
          <img src="image/kaca.avif" alt="Kaca">
          <p>Kaca</p>
        </a>
      </div>
      <div class="card">
        <a href="bautmur.html">
          <img src="image/baut.png" alt="Baut">
          <p>Baut Mur & Ring</p>
        </a>
      </div>
      <div class="card">
        <a href="jasa.html">
          <img src="image/tukang.png" alt="Jasa Pembuatan">
          <p>Jasa Pembuatan</p>
        </a>
      </div>
    </div>
  </section>

  <section id="katalog" class="keunggulan">
    <h2>Keunggulan Kami</h2>
    <div class="keunggulan-grid">
      <div class="item">📦 Stok Lengkap</div>
      <div class="item">🚚 Pengiriman Cepat</div>
      <div class="item">🛡️ Kualitas Terjamin</div>
      <div class="item">📞 Konsultasi Gratis</div>
    </div>
  </section>

  <section id="tentang" class="testimoni">
    <h2>Testimoni Pelanggan</h2>
    <div class="testi-grid">
      <blockquote>
        <p>Produk sangat berkualitas dan pengirimannya cepat!</p>
        <cite>– Budi, Kontraktor</cite>
      </blockquote>
      <blockquote>
        <p>Langganan di sini karena lengkap dan responsif CS-nya.</p>
        <cite>– Ivan, Bengkel Teknik</cite>
      </blockquote>
      <blockquote>
        <p>Ramah dan bisa di ajak konsultasi.</p>
        <cite>– ahmad, Arsitek</cite>
      </blockquote>
    </div>
  </section>

  <section id="kontak" class="kontak">
    <h2>Hubungi Kami</h2>
    <form id="kontakForm">
      <input type="text" id="nama" placeholder="Nama Lengkap" required>
      <input type="text" id="telepon" placeholder="Nomor Telepon" required>
      <textarea id="pesan" placeholder="Pesan Anda" rows="5" required></textarea>
      <button type="submit">Kirim Pesan</button>
    </form>
  </section>

  <footer>
    <div class="footer-grid">
      <div>
        <h3>Toko Alumunium mur dan baut</h3>
        <p>
          Barakah Aluminium menyediakan berbagai kebutuhan<br> aluminium,baut, mur, ring, dan aksesoris konstruksi<br>
          dengan standar kualitas tinggi dan pilihan terlengkap. <br>Kami berkomitmen menghadirkan produk unggulan<br>
          dengan harga yang kompetitif dan pelayanan yang ramah.<br><br>
          Baik Anda seorang kontraktor, tukang bangunan,<br> pemilik bengkel, ataupun individu<br> yang sedang membangun rumah impian,<br>
          kami siap membantu memenuhi kebutuhan material<br> Anda dengan cepat, aman, dan terpercaya.<br><br>
        </p>
      </div>
      <div>
        <h4>Kontak</h4>
        <p>Email: barokahalumunium@gmail.com</p>
        <p>Telp: 0831-0781-9553</p>
        <p>Alamat: Barokah Alumunium Sukorejo, W27J+WJC, <br> Beteng, Tamping Winarno, Kec. Sukorejo,<br> Kabupaten Kendal, Jawa Tengah 51363</p>
       <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3959.3515406797887!2d110.02886707356812!3d-7.085183369451186!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e706d0006cfc86d%3A0xa332a05c06d47529!2sBarokah%20Alumunium%20Sukorejo!5e0!3m2!1sen!2sid!4v1752731006932!5m2!1sen!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
      <div>
        <h4>Ikuti Kami</h4>
        <div>
          <a href="https://instagram.com" target="_blank" style="color: inherit; text-decoration: none;">
            <img src="image/ig.png" alt="Instagram" style="width:24px;height:24px;vertical-align:middle;"> Instagram
          </a><br>
          <a href="https://facebook.com" target="_blank" style="color: inherit; text-decoration: none;">
            <img src="image/fb.png" alt="Facebook" style="width:24px;height:24px;vertical-align:middle;"> Facebook
          </a><br>
          <a href="https://wa.me/6283107819553" target="_blank" style="color: inherit; text-decoration: none;">
            <img src="image/wa.png" alt="WhatsApp" style="width:24px;height:24px;vertical-align:middle;"> WhatsApp
          </a>
        </div>
      </div>
    </div>
    <p class="copyright">© Copyright 2025 || Barakah Alumunium Sukorejo</p>
  </footer>

  <script>
    document.addEventListener("DOMContentLoaded", function () {
      // === SLIDER ===
      let currentSlide = 0;
      const slides = document.querySelectorAll('.hero-slider .slide');
      const totalSlides = slides.length;

      function showSlide(index) {
        slides.forEach((slide, i) => {
          slide.classList.toggle('active', i === index);
        });
      }

      function nextSlide() {
        currentSlide = (currentSlide + 1) % totalSlides;
        showSlide(currentSlide);
      }

      function prevSlide() {
        currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
        showSlide(currentSlide);
      }

      const nextBtn = document.querySelector('.hero-slider .slide-btn.next');
      const prevBtn = document.querySelector('.hero-slider .slide-btn.prev');
      if (nextBtn) nextBtn.addEventListener('click', nextSlide);
      if (prevBtn) prevBtn.addEventListener('click', prevSlide);
      setInterval(nextSlide, 5000);

      // === SMOOTH SCROLL ===
      document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
        anchor.addEventListener("click", function(e) {
          e.preventDefault();
          const target = document.querySelector(this.getAttribute("href"));
          if (target) {
              target.scrollIntoView({ behavior: "smooth" });
          }
        });
      });

      // === FORM VALIDATION ===
      const kontakForm = document.getElementById("kontakForm");
      if (kontakForm) {
        kontakForm.addEventListener("submit", function(e) {
          e.preventDefault();
          const nama = document.getElementById("nama").value.trim();
          const telepon = document.getElementById("telepon").value.trim();
          const pesan = document.getElementById("pesan").value.trim();

          if (!nama || !telepon || !pesan) {
            alert("Semua kolom wajib diisi!");
            return;
          }

          const phonePattern = /^08[0-9]{8,11}$/;
          if (!phonePattern.test(telepon)) {
            alert("Format nomor telepon tidak valid! Contoh: 081234567890");
            return;
          }

          alert("Pesan berhasil dikirim!\n\nNama: " + nama + "\nTelepon: " + telepon + "\nPesan: " + pesan);
          kontakForm.reset();
        });
      }

      // === KERANJANG - UPDATE JUMLAH DI NAVIGASI ===
      function updateJumlahKeranjangNav() {
        const keranjang = JSON.parse(localStorage.getItem("keranjang")) || [];
        const jumlahKeranjangSpan = document.getElementById("jumlah-keranjang");
        if (jumlahKeranjangSpan) {
          jumlahKeranjangSpan.textContent = keranjang.length;
        }
      }

      updateJumlahKeranjangNav();
    });
  </script>
  
</body>
</html>
