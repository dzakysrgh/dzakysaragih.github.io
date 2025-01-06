# dzakysaragih.github.io
<!DOCTYPE html>
<html>

<head>
    <title>Toko Kami</title>
</head>

<body>
    <h1>Toko Kami</h1>
    <p>Selamat datang di toko kami! Kami menjual berbagai macam produk berkualitas dengan harga yang terjangkau.</p>
    <h2>Produk Terbaru</h2>
    <ul>
        <li>Sepatu Sneakers - Rp 200.000</li>
        <li>Jam Tangan - Rp 300.000</li>
        <li>Tas Wanita - Rp 400.000</li>
    </ul>
    <h2>Cara Pembayaran</h2>
    <p>Kami menerima pembayaran melalui transfer bank dan pembayaran langsung di toko kami.</p>
    <h2>Lokasi Toko</h2>
    <p>Anda bisa menemukan toko kami di Jalan Raya No. 123, Kota Bandung.</p>
</body>

</html>
 <!DOCTYPE html>
<html>
<head>
	<title>Toko Kami - Jual Berbagai Macam Produk Berkualitas</title>
</head>
<body>
	<header>
		<h1>Toko Kami</h1>
		<nav>
			<ul>
				<li><a href="#">Beranda</a></li>
				<li><a href="#produk">Produk</a></li>
				<li><a href="#cara-pesan">Cara Pesan</a></li>
				<li><a href="#pembayaran">Pembayaran</a></li>
				<li><a href="#lokasi">Lokasi</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="beranda">
			<h2>Selamat datang di toko kami!</h2>
			<p>Kami menjual berbagai macam produk berkualitas dengan harga yang terjangkau. Anda bisa menemukan produk-produk terbaru kami di halaman produk.</p>
		</section>
		<section id="produk">
			<h2>Produk</h2>
			<div class="produk">
				<img src="sepatu-sneakers.jpg" alt="Sepatu Sneakers">
				<h3>Sepatu Sneakers</h3>
				<p>Rp 200.000</p>
				<a href="#form-pesan">Pesan Sekarang</a>
			</div>
			<div class="produk">
				<img src="jam-tangan.jpg" alt="Jam Tangan">
				<h3>Jam Tangan</h3>
				<p>Rp 300.000</p>
				<a href="#form-pesan">Pesan Sekarang</a>
			</div>
			<div class="produk">
				<img src="tas-wanita.jpg" alt="Tas Wanita">
				<h3>Tas Wanita</h3>
				<p>Rp 400.000</p>
				<a href="#form-pesan">Pesan Sekarang</a>
			</div>
		</section>
		<section id="form-pesan">
			<h2>Form Pemesanan</h2>
			<form action="/pesan" method="post">
				<label for="nama">Nama
