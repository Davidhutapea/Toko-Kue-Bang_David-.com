<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Kue Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            color: #333;
        }
        header {
            padding: 90px;
            text-align: center;
            color: orange;
            position: relative;
            background-image: url();
        }
        nav {
            background-color: #333;
            color: rgba(255, 72, 0, 0.521);
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .banner {
            background-size: cover;
            background-position: center;
            padding: 100px 0;
            text-align: center;
            color: orangered;
        }
        .banner h1 {
            font-size: 50px;
            margin: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.384);
            box-shadow: 0 0 10px rgba(48, 163, 77, 0.178);
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-item {
            flex: 1 1 30%;
            margin: 10px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 10px;
            text-align: center;
        }
        .product-item img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .product-item h2 {
            font-size: 24px;
            margin: 15px 0;
        }
        .product-item p {
            color: #ff6f61;
            font-size: 20px;
            font-weight: bold;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Toko Kue Online</h1>
        <p>Lezat dan segar, siap dinikmati kapan saja!</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Produk</a>
        <a href="#">Tentang Kami</a>
        <a href="#">Kontak</a>
    </nav>

    <!--Banner-->
    <section class="banner">
        <h1>Selamat Datang di Toko Kue Kami</h1>
        <p>Pesan kue favoritmu dengan mudah!</p>
    </section>

    <!--Produk Item-->
    <div class="container">
        <h2>Produk Kami</h2>
        <div class="product">
            <div class="product-item">
                <img src="kue1.jpg" alt="Kue Cokelat">
                <h2>Kue Cokelat</h2>
                <p>Rp 50,000</p>
            </div>
            <div class="product-item">
                <img src="kue2.jpg" alt="Kue Keju">
                <h2>Kue Keju</h2>
                <p>Rp 55,000</p>
            </div>
            <div class="product-item">
                <img src="kue3.jpg" alt="Kue Stroberi">
                <h2>Kue Stroberi</h2>
                <p>Rp 60,000</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Toko Kue Online. Semua Hak Cipta Dilindungi.</p>
    </footer>

</body>
</html>
