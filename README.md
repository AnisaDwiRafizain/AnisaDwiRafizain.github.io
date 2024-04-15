<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halaman E-commerce Sederhana</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f0f0f0; /* Abu Muda */
            padding: 20px;
            text-align: center;
        }
        nav {
            margin-top: 10px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
        }
        .container {
            display: flex;
            justify-content: center;
            align-items: flex-start;
            flex-wrap: wrap;
            padding: 20px;
        }
        .product {
            width: 300px;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f9f9f9;
            text-align: center;
        }
        .product img {
            width: 200px;
            height: 200px;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Halaman E-commerce Sederhana</h1>
        <nav>
            <ul>
                <li><a href="#">Beranda</a></li>
                <li><a href="#">Produk</a></li>
                <li><a href="#">Keranjang</a></li>
                <li><a href="#">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <div class="product">
            <img src="img1.webp">
            <h2>Bunny Plushie</h2>
            <p>Harga: Rp. 262.000,00</p>
            <button>Beli</button>
        </div>
        <div class="product">
            <img src="img2.jpg">
            <h2>My Melody Plushie</h2>
            <p>Harga: Rp. 120.000,00</p>
            <button>Beli</button>
          </div>
        <div class="product">
            <img src="img3.jpg">
            <h2>Kuromi Plushie</h2>
            <p>Harga: Rp. 120.000,00</p>
            <button>Beli</button>
          </div>
        <div class="product">
            <img src="img4.jpg">
            <h2>Pingu Plushie</h2>
            <p>Harga: Rp. 250.000,00</p>
            <button>Beli</button>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 - Anisa Plushie Store</p>
    </footer>
</body>
</html>
