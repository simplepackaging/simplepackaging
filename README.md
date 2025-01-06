<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Pack - Brand Tempat Makan</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f1; /* Warna hijau nude */
        }
        header {
            background-color: #ffffff; /* Putih */
            color: #333;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ffffff; /* Putih */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 10px 0;
        }
        nav a {
            color: #333;
            padding: 14px 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff9800;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background-color: #e0f2e9; /* Hijau nude */
        }
        .hero h1 {
            font-size: 2.5rem;
            color: #333;
        }
        .hero p {
            font-size: 1.2rem;
            color: #555;
        }
        .about, .product-section, .social-media {
            padding: 20px;
            text-align: center;
        }
        .product-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            background-color: #ffffff; /* Putih */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product h3 {
            margin: 10px 0 5px;
            color: #333;
        }
        .product p {
            margin: 0;
            font-weight: bold;
            color: #ff9800;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .social-media a {
            margin: 0 10px;
            display: inline-block;
        }
        .social-media a img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
        }
        .social-media a:hover img {
            opacity: 0.8;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Simple Pack Logo" style="height: 40px; vertical-align: middle; margin-right: 10px;"> 
            Simple Pack
        </h1>
        <p>Brand tempat makan sederhana dengan cita rasa istimewa</p>
    </header>

    <nav>
        <a href="#about">Tentang Kami</a>
        <a href="#product">Produk</a>
        <a href="#social-media">Sosial Media</a>
    </nav>

    <section class="hero">
        <h1>Selamat Datang di Simple Pack</h1>
        <p>Hemat Tempat, Mudah Dibawa, Simple Pack Solusinya!.</p>
    </section>

    <section id="about" class="about">
        <h2>Tentang Simple Pack</h2>
        <p>Simple Pack adalah Wadah untuk Snacktray Cup Slim merujuk pada solusi kemasan yang sederhana dan efisien untuk wadah camilan yang dirancang untuk menampung porsi kecil camilan. Kemasan jenis ini biasanya minimalis, lebih menekankan pada fungsi ketimbang desain atau fitur yang rumit. Snacktray Cup Slim menggambarkan wadah camilan yang kompak, mudah dibawa, dan praktis, yang biasanya digunakan untuk porsi tunggal atau porsi kecil.</p>
    </section>

    <section id="product" class="product-section">
        <h2>Produk Kami</h2>
        <div class="product">
            <h3>Tempat Makan</h3>
            <p>Rp7.000</p>
            <img src="blob:https://imgur.com/8a2b72f1-5d8f-4da3-a6f5-6fd54f8fb84d" alt="Tempat Makan">
        </div>
        <div class="product">
            <h3>Tempat Minum</h3>
            <p>Rp5.000</p>
            <img src="https://i.imgur.com/Gm3GLuu.jpeg" alt="Tempat Minum">
        </div>
    </section>

    <section id="social-media" class="social-media">
        <h2>Ikuti Kami</h2>
        <p>Temukan kami di platform berikut:</p>
        <a href="https://www.tiktok.com/@simplepack.ok?_t=ZS-8spaen8B1CU&_r=1" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/63/TikTok_logo_2021.svg" alt="TikTok" style="width: 40px; height: 40px; border-radius: 50%;">
        </a>
        <a href="https://www.facebook.com/profile.php?id=61558444066129&mibextid=LQQJ4d" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook" style="width: 40px; height: 40px; border-radius: 50%;">
        </a>
        <a href="https://www.instagram.com/simplepack.ok/profilecard/?igsh=MTc4bHc1Z3BvanB6MA==" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" style="width: 40px; height: 40px; border-radius: 50%;">
        </a>
        <a href="https://wa.me/6285939404874" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" style="width: 40px; height: 40px; border-radius: 50%;">
        </a>
        <a href="mailto:simplepack7@gmail.com" target="_blank">
            <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" alt="Email" style="width: 40px; height: 40px; border-radius: 50%;">
        </a>
    </section>

    <footer>
        <p>&copy; 2025 Simple Pack. All rights reserved.</p>
    </footer>
</body>
</html>
