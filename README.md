<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perjalanan Cinta Kami - 4 Bulan Bersama</title>
    <style>
        /* Reset dan font elegan */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Montserrat', sans-serif; /* Font modern seperti di situs Ferrari */
            background: linear-gradient(135deg, #ff6b6b, #feca57, #48cae4); /* Background cinta dengan gradien warna-warni */
            color: #333;
            overflow-x: hidden; /* Mencegah scroll horizontal tidak diinginkan */
            scroll-behavior: smooth; /* Scroll smooth vertikal */
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 50px 0;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 3em;
            color: #d63031; /* Warna merah Ferrari */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        .section {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 50px;
            background: rgba(255, 255, 255, 0.8);
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease; /* Efek hover seperti Ferrari */
        }
        .section:hover {
            transform: translateY(-10px);
        }
        .story {
            text-align: center;
            max-width: 800px;
        }
        .story h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #2d3436;
        }
        .story p {
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .gallery {
            display: flex;
            overflow-x: auto; /* Scroll horizontal seperti situs Ferrari */
            scroll-behavior: smooth;
            gap: 20px;
            padding: 20px;
            background: rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            scrollbar-width: none; /* Sembunyikan scrollbar untuk efek elegan */
        }
        .gallery::-webkit-scrollbar {
            display: none;
        }
        .photo {
            flex: 0 0 300px;
            height: 300px;
            background-size: cover;
            background-position: center;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .photo:hover {
            transform: scale(1.05);
        }
        /* Placeholder untuk foto - ganti dengan URL foto asli */
        .photo1 { background-image: url('https://via.placeholder.com/300x300?text=Foto+1'); }
        .photo2 { background-image: url('https://via.placeholder.com/300x300?text=Foto+2'); }
        .photo3 { background-image: url('https://via.placeholder.com/300x300?text=Foto+3'); }
        .photo4 { background-image: url('https://via.placeholder.com/300x300?text=Foto+4'); }
        .photo5 { background-image: url('https://via.placeholder.com/300x300?text=Foto+5'); }
        .photo6 { background-image: url('https://via.placeholder.com/300x300?text=Foto+6'); }
        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            color: white;
            font-size: 1em;
        }
        /* Efek parallax untuk vibe Ferrari (scroll vertikal dengan efek latar belakang) */
        .parallax {
            background-attachment: fixed;
            background-size: cover;
            background-position: center;
        }
        .parallax1 { background-image: url('https://via.placeholder.com/1920x1080?text=Background+Cinta+1'); }
        .parallax2 { background-image: url('https://via.placeholder.com/1920x1080?text=Background+Cinta+2'); }
        /* Animasi masuk seperti di situs Ferrari */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .section {
            animation: fadeIn 1s ease-out;
        }
        /* Navigasi smooth dengan tombol */
        .nav {
            position: fixed;
            top: 50%;
            right: 20px;
            transform: translateY(-50%);
            z-index: 1000;
        }
        .nav button {
            display: block;
            margin: 10px 0;
            padding: 10px 15px;
            background: #d63031;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .nav button:hover {
            background: #b71540;
        }
    </style>
</head>
<body>
    <!-- Navigasi untuk scroll smooth -->
    <div class="nav">
        <button onclick="scrollToSection('bulan1')">Bulan 1</button>
        <button onclick="scrollToSection('bulan2')">Bulan 2</button>
        <button onclick="scrollToSection('bulan3')">Bulan 3</button>
        <button onclick="scrollToSection('bulan4')">Bulan 4</button>
        <button onclick="scrollToSection('galeri')">Galeri</button>
    </div>

    <header>
        <div class="container">
            <h1>Perjalanan Cinta Kami: 4 Bulan Bersama</h1>
            <p>Sebuah kenangan indah yang tak terlupakan.</p>
        </div>
    </header>

    <section id="bulan1" class="section parallax parallax1">
        <div class="container story">
            <h2>Bulan 1: Pertemuan Pertama</h2>
            <p>Di bulan pertama, aku melakukan banyak kesalah aku sangat minta maaf, aku sangat bersyukur kita bisa sejauh ini makasih my baby honey ku.</p>
        </div>
    </section>

    <section id="bulan2" class="section parallax parallax2">
        <div class="container story">
            <h2>Bulan 2: Mengenal Lebih Dalam</h2>
            <p>Bulan kedua penuh dengan petualangan. aku masih membuat masalah aku sangat minta maaf, but im so happy kamu selalu ada disisi aku sayang makasih banyak yah cinta.</p>
        </div>
    </section>

    <section id="bulan3" class="section parallax parallax1">
        <div class="container story">
            <h2>Bulan 3: Tantangan dan Kekuatan</h2>
            <p>Di bulan ketiga, ada tantangan yang kita hadapi bersama. Tapi itu justru membuat hubungan kita lebih kuat. Kita saling mendukung, dan aku semakin yakin bahwa kamu adalah orang yang tepat.</p>
        </div>
    </section>

    <section id="bulan4" class="section parallax parallax2">
        <div class="container story">
            <h2>Bulan 4: Masa Depan Bersama</h2>
            <p>Bulan keempat ini penuh harapan. Kita merencanakan masa depan, berbagi impian, dan aku tidak sabar untuk menghabiskan lebih banyak waktu bersamamu. Cintaku padamu semakin dalam setiap hari.</p>
        </div>
    </section>

    <section id="galeri" class="section">
        <div class="container">
            <h2>Galeri Kenangan Kami</h2>
            <div class="gallery">
                <div class="photo photo1"></div>
                <div class="photo photo2"></div>
                <div class="photo photo3"></div>
                <div class="photo photo4"></div>
                <div class="photo photo5"></div>
                <div class="photo photo6"></div>
            </div>
            <p>Geser ke kiri atau kanan untuk melihat lebih banyak foto. (Gunakan mouse atau touch pada perangkat mobile.)</p>
        </div>
    </section>

    <footer>
        <p>Dibuat dengan cinta untukmu. © 2023</p>
    </footer>

    <script>
        // Fungsi untuk scroll smooth ke section tertentu (seperti navigasi di situs Ferrari)
        function scrollToSection(id) {
            const element = document.getElementById(id);
            element.scrollIntoView({ behavior: 'smooth' });
        }

        // Efek tambahan: Parallax sederhana untuk vibe Ferrari
        window.addEventListener('scroll', function() {
            const scrolled = window.pageYOffset;
            const parallaxElements = document.querySelectorAll('.parallax');
            parallaxElements.forEach(el => {
                el.style.backgroundPositionY = -(scrolled * 0.5) + 'px';
            });
        });

        // Animasi fade-in saat scroll (fitur elegan)
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = 1;
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        });
        document.querySelectorAll('.section').forEach(section => {
            observer.observe(section);
        });
    </script>
</body>
</html>
