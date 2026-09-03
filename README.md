<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes" />
  <title>Indie Yulvina P. | Pelajar • SMKN 42 Jakarta</title>
  <meta name="description" content="Profil personal Indie Yulvina P. — Pelajar SMKN 42 Jakarta. Create. Inspire. Impact. Portofolio, CV, artikel, dan kontak." />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='24' fill='%231f3a5f'/%3E%3Ctext x='50' y='68' font-size='50' font-family='Poppins, sans-serif' font-weight='700' fill='%23d4b483' text-anchor='middle'%3EIY%3C/text%3E%3C/svg%3E" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg: #f9fafc;
      --bg-alt: #ffffff;
      --text: #1a1a2e;
      --text-secondary: #3d3d56;
      --accent: #1f3a5f;
      --accent-soft: #d4b483;
      --border: #eaeef2;
      --shadow: 0 12px 28px -12px rgba(0,0,0,0.06), 0 6px 18px -8px rgba(0,0,0,0.02);
      --radius: 24px;
      --radius-sm: 16px;
      --transition: 0.25s cubic-bezier(0.2, 0, 0, 1);
      --max-width: 1200px;
      --font-head: 'Plus Jakarta Sans', sans-serif;
      --font-body: 'Inter', sans-serif;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    html { scroll-behavior: smooth; font-size: 16px; }
    body {
      font-family: var(--font-body);
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      transition: background 0.3s, color 0.3s;
      -webkit-font-smoothing: antialiased;
      overflow-x: hidden;
    }
    body.dark {
      --bg: #12121a;
      --bg-alt: #1c1c26;
      --text: #f0f0f5;
      --text-secondary: #c0c0cf;
      --border: #2c2c3a;
      --shadow: 0 16px 32px rgba(0,0,0,0.3);
    }
    h1, h2, h3, h4, h5 { font-family: var(--font-head); font-weight: 700; line-height: 1.25; letter-spacing: -0.02em; }
    a { color: inherit; text-decoration: none; }
    img { max-width: 100%; display: block; }
    .container { width: 100%; max-width: var(--max-width); margin: 0 auto; padding: 0 2rem; }
    @media (max-width: 600px) { .container { padding: 0 1.25rem; } }

    /* Navbar */
    .navbar {
      position: fixed; top: 0; left: 0; width: 100%;
      background: rgba(249,250,252,0.85);
      backdrop-filter: blur(14px); -webkit-backdrop-filter: blur(14px);
      border-bottom: 1px solid var(--border);
      z-index: 1000; transition: background 0.3s, border 0.3s;
    }
    body.dark .navbar { background: rgba(18,18,26,0.85); }
    .nav-container { display: flex; align-items: center; justify-content: space-between; padding: 0.8rem 2rem; max-width: var(--max-width); margin: 0 auto; }
    .logo { font-family: var(--font-head); font-weight: 800; font-size: 1.6rem; letter-spacing: -0.03em; color: var(--accent); }
    .nav-menu { display: flex; align-items: center; gap: 1.8rem; list-style: none; }
    .nav-menu a { font-weight: 500; font-size: 0.95rem; color: var(--text-secondary); position: relative; padding: 0.3rem 0; transition: color 0.2s; }
    .nav-menu a::after { content: ''; position: absolute; left: 0; bottom: -2px; width: 0; height: 2px; background: var(--accent-soft); transition: width 0.25s; }
    .nav-menu a:hover, .nav-menu a.active { color: var(--accent); }
    .nav-menu a:hover::after, .nav-menu a.active::after { width: 100%; }
    .hamburger { display: none; flex-direction: column; gap: 5px; cursor: pointer; background: transparent; border: none; padding: 0.25rem; }
    .hamburger span { display: block; width: 26px; height: 2.5px; background: var(--text); border-radius: 4px; transition: 0.3s; }
    .dark-toggle { background: transparent; border: 1px solid var(--border); border-radius: 40px; width: 44px; height: 24px; position: relative; cursor: pointer; margin-left: 1rem; }
    .dark-toggle::after { content: '☀️'; position: absolute; top: 50%; left: 4px; transform: translateY(-50%); font-size: 14px; transition: 0.3s; }
    body.dark .dark-toggle::after { content: '🌙'; left: 24px; }

    @media (max-width: 900px) {
      .nav-menu { position: fixed; top: 70px; right: -100%; width: 75%; max-width: 320px; height: auto; background: var(--bg-alt); box-shadow: var(--shadow); border-radius: var(--radius-sm); flex-direction: column; padding: 2rem 1.5rem; gap: 1.5rem; transition: right 0.35s ease; border: 1px solid var(--border); }
      .nav-menu.open { right: 20px; }
      .hamburger { display: flex; }
      .dark-toggle { margin-left: 0.5rem; }
    }

    .btn { display: inline-flex; align-items: center; justify-content: center; gap: 0.5rem; font-weight: 600; font-family: var(--font-head); border-radius: 50px; padding: 0.9rem 2rem; border: 1px solid transparent; cursor: pointer; transition: all 0.25s; letter-spacing: 0.01em; }
    .btn-primary { background: var(--accent); color: #fff; box-shadow: 0 10px 20px -8px rgba(31,58,95,0.3); }
    .btn-primary:hover { background: #17304d; transform: translateY(-3px); box-shadow: 0 18px 28px -10px rgba(31,58,95,0.4); }
    .btn-outline { background: transparent; border: 1.5px solid var(--accent); color: var(--accent); }
    .btn-outline:hover { background: var(--accent); color: #fff; transform: translateY(-3px); }

    section { padding: 5rem 0; }
    .section-title { font-size: 2.5rem; margin-bottom: 2rem; font-weight: 700; text-align: center; }
    .grid-2col { display: grid; grid-template-columns: 1fr 1fr; gap: 3rem; align-items: center; }
    @media (max-width: 800px) { .grid-2col { grid-template-columns: 1fr; } }
    .card { background: var(--bg-alt); border-radius: var(--radius); padding: 1.8rem; box-shadow: var(--shadow); border: 1px solid var(--border); transition: transform 0.2s; }
    .card:hover { transform: translateY(-6px); }

    .hero { min-height: 92vh; display: flex; align-items: center; padding: 7rem 0 3rem; }
    .hero-grid { display: grid; grid-template-columns: 1.1fr 0.9fr; gap: 3rem; align-items: center; }
    .hero-content h1 { font-size: 3.4rem; font-weight: 800; margin-bottom: 0.5rem; }
    .profession { font-size: 1.3rem; font-weight: 500; color: var(--text-secondary); margin: 0.4rem 0 0.2rem; }
    .tagline { font-size: 1rem; color: var(--accent-soft); font-weight: 600; margin-bottom: 1.8rem; }
    .hero-buttons { display: flex; gap: 1rem; flex-wrap: wrap; margin: 2rem 0 1.2rem; }
    .social-icons { display: flex; gap: 1rem; margin-top: 0.8rem; }
    .social-icons a { display: inline-flex; width: 42px; height: 42px; border-radius: 40px; background: var(--bg-alt); border: 1px solid var(--border); align-items: center; justify-content: center; color: var(--text); transition: 0.2s; }
    .social-icons a:hover { background: var(--accent); color: white; border-color: var(--accent); }
    .hero-image img { width: 100%; max-width: 420px; aspect-ratio: 1/1; object-fit: cover; border-radius: 50% 20% 50% 20%; box-shadow: var(--shadow); border: 4px solid white; background: #ddd; margin-left: auto; }
    @media (max-width: 800px) { .hero-grid { grid-template-columns: 1fr; text-align: center; } .hero-image img { margin: 0 auto; max-width: 280px; } }

    .filter-buttons { display: flex; gap: 0.8rem; flex-wrap: wrap; margin-bottom: 2rem; justify-content: center; }
    .filter-btn { padding: 0.5rem 1.4rem; border-radius: 40px; border: 1px solid var(--border); background: var(--bg-alt); font-weight: 500; cursor: pointer; transition: 0.2s; }
    .filter-btn.active, .filter-btn:hover { background: var(--accent); color: white; border-color: var(--accent); }
    .works-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(260px, 1fr)); gap: 1.8rem; }
    .work-card img { height: 180px; width: 100%; object-fit: cover; border-radius: var(--radius-sm); background: #ccc; }
    .work-card .work-info { padding: 1rem 0.2rem; }

    .gallery-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); gap: 1.2rem; }
    .gallery-item img { border-radius: var(--radius-sm); aspect-ratio: 1/1; object-fit: cover; width: 100%; cursor: pointer; transition: 0.25s; }
    .gallery-item img:hover { transform: scale(0.98); }

    .social-link-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 1.5rem; text-align: center; }
    .social-link-card { background: var(--bg-alt); border-radius: var(--radius-sm); padding: 1.5rem 0.5rem; border: 1px solid var(--border); transition: 0.2s; }
    .social-link-card:hover { border-color: var(--accent); }

    .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 2.5rem; margin-bottom: 3rem; }
    .form-group { margin-bottom: 1.2rem; }
    input, textarea { width: 100%; padding: 0.9rem 1rem; border-radius: 14px; border: 1px solid var(--border); background: var(--bg-alt); font-family: var(--font-body); font-size: 0.95rem; transition: 0.2s; }
    input:focus, textarea:focus { outline: none; border-color: var(--accent); box-shadow: 0 0 0 4px rgba(31,58,95,0.1); }
    .testimonial-carousel { display: flex; gap: 1.5rem; overflow-x: auto; scroll-snap-type: x mandatory; padding-bottom: 1rem; scrollbar-width: thin; }
    .testimonial-card { scroll-snap-align: start; min-width: 280px; background: var(--bg-alt); border-radius: var(--radius); padding: 1.8rem; border: 1px solid var(--border); box-shadow: var(--shadow); }
    .stars { color: #f1c40f; letter-spacing: 2px; }

    footer { background: var(--bg-alt); padding: 3rem 0 2rem; border-top: 1px solid var(--border); }
    .back-to-top { position: fixed; bottom: 25px; right: 25px; background: var(--accent); color: white; width: 45px; height: 45px; border-radius: 40px; display: flex; align-items: center; justify-content: center; cursor: pointer; border: none; box-shadow: var(--shadow); opacity: 0.7; }
    .lightbox { position: fixed; inset: 0; background: rgba(0,0,0,0.85); display: none; align-items: center; justify-content: center; z-index: 2000; cursor: zoom-out; }
    .lightbox.active { display: flex; }
    .lightbox img { max-height: 90vh; max-width: 90vw; border-radius: 16px; }
  </style>
</head>
<body>
  <header class="navbar" id="navbar">
    <div class="nav-container">
      <div class="logo">Indie<span style="color: var(--accent-soft);">.</span></div>
      <nav>
        <ul class="nav-menu" id="nav-menu">
          <li><a href="#beranda" class="active">Beranda</a></li>
          <li><a href="#tentang">Tentang Kami</a></li>
          <li><a href="#cv">CV</a></li>
          <li><a href="#karya">Hasil Karya</a></li>
          <li><a href="#artikel">Foto Artikel</a></li>
          <li><a href="#sosmed">Media Sosial</a></li>
          <li><a href="#kontak">Kontak & Testimoni</a></li>
        </ul>
      </nav>
      <div style="display: flex; align-items: center;">
        <button class="dark-toggle" id="darkToggle" aria-label="Dark mode"></button>
        <button class="hamburger" id="hamburger" aria-label="Menu"><span></span><span></span><span></span></button>
      </div>
    </div>
  </header>

  <main>
    <!-- Beranda -->
    <section id="beranda" class="hero">
      <div class="container hero-grid">
        <div class="hero-content">
          <h1>Indie Yulvina P.</h1>
          <div class="profession">Pelajar</div>
          <div class="tagline">Sekarang di SMKN 42 Jakarta</div>
          <p style="font-size: 1.2rem; font-weight: 400; color: var(--text-secondary);">Create. Inspire. Impact.</p>
          <div class="hero-buttons">
            <a href="#karya" class="btn btn-primary">Lihat Hasil Karya</a>
            <a href="#kontak" class="btn btn-outline">Hubungi Saya</a>
          </div>
          <div class="social-icons">
            <a href="#" aria-label="instagram">📷</a>
            <a href="#" aria-label="tiktok">🎵</a>
            <a href="#" aria-label="whatsapp">💬</a>
            <a href="#" aria-label="email">✉️</a>
          </div>
        </div>
        <div class="hero-image">
          <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='400' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%231f3a5f'/%3E%3Ccircle cx='50' cy='40' r='18' fill='%23f0f0f5'/%3E%3Ccircle cx='50' cy='75' r='25' fill='%23f0f0f5'/%3E%3C/svg%3E" alt="Foto profil Indie Yulvina P." />
        </div>
      </div>
    </section>

    <!-- Tentang Kami -->
    <section id="tentang">
      <div class="container">
        <h2 class="section-title">Tentang Kami</h2>
        <div class="grid-2col">
          <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='400' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%23d4b483'/%3E%3Ccircle cx='50' cy='45' r='20' fill='white'/%3E%3Crect x='30' y='65' width='40' height='30' rx='10' fill='white'/%3E%3C/svg%3E" alt="Foto biografi" style="border-radius: var(--radius); box-shadow: var(--shadow); max-width: 320px;"/>
          <div>
            <p style="margin-bottom: 1rem;"><strong>Biografi:</strong> Saya adalah pribadi yang memiliki semangat untuk terus belajar, berkembang, dan menghasilkan karya yang bermanfaat. Setiap pengalaman yang saya jalani menjadi bagian penting dalam membentuk karakter, wawasan, serta cara saya dalam berkarya dan berkontribusi.</p>
            <p style="margin-bottom: 1rem;"><strong>Latar Belakang:</strong> Lahir dan besar di Jakarta, saat ini menempuh pendidikan di SMKN 42 Jakarta dengan fokus pada pengembangan diri dan kewirausahaan.</p>
            <p><strong>Visi:</strong> Menjadi pribadi dan profesional yang inspiratif, berintegritas, serta mampu menghasilkan karya yang berkualitas, bermanfaat, dan memberikan dampak positif bagi masyarakat serta lingkungan sekitar.</p>
            <p style="margin-top: 0.8rem;"><strong>Misi:</strong> Mengembangkan diri secara berkelanjutan, menghasilkan karya berkualitas, memberikan manfaat melalui ilmu dan pengalaman, membangun kolaborasi positif, menjaga integritas, serta beradaptasi dengan perkembangan zaman.</p>
            <p style="margin-top: 1rem;"><strong>Keahlian:</strong> Berwirausaha, Dance, Cooking.</p>
            <p><strong>Pengalaman:</strong> Perjalanan pengalaman saya merupakan proses yang terus berkembang melalui berbagai peran, tanggung jawab, dan kesempatan untuk belajar.</p>
            <p><strong>Pencapaian:</strong> Menjadi siswi terbaik nomor 1 di sekolah.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CV -->
    <section id="cv">
      <div class="container">
        <h2 class="section-title">Curriculum Vitae</h2>
        <div style="display: flex; justify-content: center; margin-bottom: 2rem;">
          <button class="btn btn-primary" onclick="alert('CV berhasil diunduh (dummy)')">Download CV</button>
        </div>
        <div class="grid-2col" style="gap: 1.5rem;">
          <div class="card"><h3>Profil Singkat</h3><p>Pelajar</p></div>
          <div class="card"><h3>Pendidikan</h3><p>SMK</p></div>
          <div class="card"><h3>Pengalaman Kerja</h3><p>Berwirausaha</p></div>
          <div class="card"><h3>Pengalaman Organisasi</h3><p>OSIS, Ketua ekstrakulikuler, Pramuka</p></div>
          <div class="card"><h3>Keahlian</h3><p>Berwirausaha, Public Speaking, Dance, Cooking</p></div>
          <div class="card"><h3>Sertifikat</h3><p>Perkemahan Pramuka, Lomba Menggambar, Siswi Terbaik</p></div>
          <div class="card"><h3>Penghargaan</h3><p>Juara 3 PBB & Favor, Siswi terbaik nomor 1</p></div>
        </div>
      </div>
    </section>

    <!-- Hasil Karya -->
    <section id="karya">
      <div class="container">
        <h2 class="section-title">Hasil Karya</h2>
        <div class="filter-buttons">
          <button class="filter-btn active" data-filter="semua">Semua</button>
          <button class="filter-btn" data-filter="desain">Desain</button>
          <button class="filter-btn" data-filter="website">Website</button>
          <button class="filter-btn" data-filter="foto">Foto</button>
          <button class="filter-btn" data-filter="video">Video</button>
          <button class="filter-btn" data-filter="proyek">Proyek Lainnya</button>
        </div>
        <div class="works-grid" id="worksGrid">
          <div class="work-card" data-category="desain"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='250' viewBox='0 0 100 60'%3E%3Crect width='100' height='60' fill='%231f3a5f'/%3E%3Ctext x='50' y='35' fill='white' font-size='10' text-anchor='middle'%3EDesain Poster%3C/text%3E%3C/svg%3E" /><div class="work-info"><h4>Poster Kreatif</h4><p>Desain · 2024</p><button class="btn btn-outline" style="padding:0.4rem 1rem;">Lihat Detail</button></div></div>
          <div class="work-card" data-category="website"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='250' viewBox='0 0 100 60'%3E%3Crect width='100' height='60' fill='%23d4b483'/%3E%3Ctext x='50' y='35' fill='black' font-size='10' text-anchor='middle'%3EProfil Website%3C/text%3E%3C/svg%3E" /><div class="work-info"><h4>Landing Page</h4><p>Website · 2024</p><button class="btn btn-outline" style="padding:0.4rem 1rem;">Lihat Detail</button></div></div>
          <div class="work-card" data-category="foto"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='250' viewBox='0 0 100 60'%3E%3Crect width='100' height='60' fill='%23333'/%3E%3Ctext x='50' y='35' fill='white' font-size='10' text-anchor='middle'%3EFotografi%3C/text%3E%3C/svg%3E" /><div class="work-info"><h4>Foto Produk</h4><p>Foto · 2023</p><button class="btn btn-outline" style="padding:0.4rem 1rem;">Lihat Detail</button></div></div>
          <div class="work-card" data-category="video"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='250' viewBox='0 0 100 60'%3E%3Crect width='100' height='60' fill='%23222'/%3E%3Ctext x='50' y='35' fill='white' font-size='10' text-anchor='middle'%3EVideo Pendek%3C/text%3E%3C/svg%3E" /><div class="work-info"><h4>Video Dokumenter</h4><p>Video · 2024</p><button class="btn btn-outline" style="padding:0.4rem 1rem;">Lihat Detail</button></div></div>
          <div class="work-card" data-category="proyek"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='250' viewBox='0 0 100 60'%3E%3Crect width='100' height='60' fill='%23544'/%3E%3Ctext x='50' y='35' fill='white' font-size='10' text-anchor='middle'%3EProyek Lain%3C/text%3E%3C/svg%3E" /><div class="work-info"><h4>Event Organizer</h4><p>Proyek Lainnya · 2024</p><button class="btn btn-outline" style="padding:0.4rem 1rem;">Lihat Detail</button></div></div>
        </div>
      </div>
    </section>

    <!-- Foto Artikel -->
    <section id="artikel">
      <div class="container">
        <h2 class="section-title">Foto Artikel</h2>
        <div class="gallery-grid" id="galleryGrid">
          <div class="gallery-item"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='300' height='300' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%2390a4c2'/%3E%3Ctext x='50' y='55' fill='white' font-size='12' text-anchor='middle'%3EDokumentasi%3C/text%3E%3C/svg%3E" alt="Foto dokumentasi 1" onclick="openLightbox(this.src)"></div>
          <div class="gallery-item"><img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='300' height='300' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%23b58c6b'/%3E%3Ctext x='50' y='55' fill='white' font-size='12' text-anchor='middle'%3EArtikel%3C/text%3E%3C/svg%3E" alt="Foto artikel" onclick="openLightbox(this.src)"></div>
        </div>
        <div style="margin-top: 2rem;" class="card">
          <h4>Artikel: "Create, Inspire, Impact"</h4>
          <p>12 Februari 2025 · Kategori Inspirasi</p>
          <p>Bagaimana pelajar SMK dapat menciptakan dampak melalui karya sederhana.</p>
          <button class="btn btn-outline" style="margin-top:0.5rem;">Baca Selengkapnya</button>
        </div>
      </div>
    </section>

    <!-- Link Media Sosial -->
    <section id="sosmed">
      <div class="container">
        <h2 class="section-title">Media Sosial</h2>
        <div class="social-link-grid">
          <div class="social-link-card">📷 Instagram<br>@bondiiee</div>
          <div class="social-link-card">📘 Facebook<br>-</div>
          <div class="social-link-card">▶️ YouTube<br>-</div>
          <div class="social-link-card">🎵 TikTok<br>indieciken</div>
          <div class="social-link-card">💼 LinkedIn<br>-</div>
          <div class="social-link-card">🐦 X/Twitter<br>-</div>
          <div class="social-link-card">💬 WhatsApp<br>0877-7184-0886</div>
          <div class="social-link-card">🌐 Website<br>-</div>
        </div>
      </div>
    </section>

    <!-- Kontak & Testimoni -->
    <section id="kontak">
      <div class="container">
        <h2 class="section-title">Kontak & Testimoni</h2>
        <div class="contact-grid">
          <div>
            <p>📧 indieyulvinaputri@gmail.com</p>
            <p>📱 0877-7184-0886</p>
            <p>📍 Jl. Kapuk Gg Masjid Al-Munawwaroh rt15/11</p>
            <p>🕘 Jam kontak: -</p>
            <button class="btn btn-primary" style="margin-top:1rem;" onclick="alert('Menghubungi WhatsApp')">💬 Chat WhatsApp</button>
          </div>
          <div>
            <form onsubmit="alert('Pesan terkirim (dummy)'); return false;">
              <div class="form-group"><input type="text" placeholder="Nama" value="Indie Yulvina P." required></div>
              <div class="form-group"><input type="email" placeholder="Email" value="indieyulvinaputri@gmail.com" required></div>
              <div class="form-group"><input type="tel" placeholder="Nomor WhatsApp" value="0877-7184-0886"></div>
              <div class="form-group"><input type="text" placeholder="Subjek"></div>
              <div class="form-group"><textarea rows="3" placeholder="Pesan"></textarea></div>
              <button class="btn btn-primary" type="submit">Kirim Pesan</button>
            </form>
          </div>
        </div>
        <h3 style="margin-bottom: 1rem;">Testimoni</h3>
        <div class="testimonial-carousel">
          <div class="testimonial-card"><div class="stars">★★★★★</div><p>"Karya dan semangatnya luar biasa!"</p><p><strong>Indie Yulvina P.</strong> — Pelajar</p></div>
          <div class="testimonial-card"><div class="stars">★★★★☆</div><p>"Sangat menginspirasi dan komunikatif."</p><p><strong>Indie Yulvina P.</strong> — Pelajar</p></div>
          <div class="testimonial-card"><div class="stars">★★★★★</div><p>"Berbakat dan profesional."</p><p><strong>Indie Yulvina P.</strong> — Pelajar</p></div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container" style="display: flex; justify-content: space-between; flex-wrap: wrap; gap: 2rem;">
      <div><h3>Indie Yulvina P.</h3><p>Create. Inspire. Impact.</p><p>© 2025 Indie. All rights reserved.</p></div>
      <div><a href="#beranda">Beranda</a> · <a href="#tentang">Tentang</a> · <a href="#karya">Karya</a></div>
      <div>📧 indieyulvinaputri@gmail.com</div>
    </div>
  </footer>

  <button class="back-to-top" id="backToTop" aria-label="Kembali ke atas">↑</button>
  <div class="lightbox" id="lightbox" onclick="this.classList.remove('active')">
    <img src="#" alt="lightbox" id="lightboxImg">
  </div>

  <script>
    const menu = document.getElementById('nav-menu');
    const hamburger = document.getElementById('hamburger');
    hamburger.addEventListener('click', () => menu.classList.toggle('open'));
    document.querySelectorAll('.nav-menu a').forEach(link => {
      link.addEventListener('click', () => menu.classList.remove('open'));
    });

    const darkToggle = document.getElementById('darkToggle');
    darkToggle.addEventListener('click', () => {
      document.body.classList.toggle('dark');
    });

    const backBtn = document.getElementById('backToTop');
    backBtn.addEventListener('click', () => window.scrollTo({top:0, behavior:'smooth'}));

    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
      });
    });

    const filterBtns = document.querySelectorAll('.filter-btn');
    const workCards = document.querySelectorAll('.work-card');
    filterBtns.forEach(btn => {
      btn.addEventListener('click', () => {
        filterBtns.forEach(b => b.classList.remove('active'));
        btn.classList.add('active');
        const filter = btn.dataset.filter;
        workCards.forEach
