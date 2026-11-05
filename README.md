# CV-saya 

<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>CV Pribadi</title>

<style>
* { box-sizing: border-box; }

body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: white;
  background: #111;
}

video {
  position: fixed;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -2;
}

body::before {
  content: "";
  position: fixed;
  inset: 0;
  background: #080808b8;
  z-index: -1;
}

.container {
  max-width: 750px;
  margin: 60px auto;
  padding: 20px;
}

.card {
  background: #ffffff12;
  border: 1px solid #ffffff25;
  backdrop-filter: blur(15px);
  border-radius: 20px;
  padding: 30px;
  margin-bottom: 20px;
}

h1 { font-size: 38px; }
h2 { color: #aaa; }

span { color: #aaa; }

li { margin: 12px 0; }

@media(max-width:600px) {
  .container { margin: 20px auto; }
  h1 { font-size: 30px; }
}
</style>
</head>

<body>

<!-- Background video MP4 -->
<video autoplay muted loop playsinline>
  <source src="aku.mp4" type="video/mp4">
</video>

<div class="container">

  <section class="card">
    <h1>Aditya idris</h1>
    <p>Pelajar | Gamer | Pecinta Anime</p>
    <p>Selamat datang di profil pribadi saya.</p>
  </section>

  <section class="card">
    <h2>Data Diri</h2>
    <p>Nama: Aditya idris</p>
    <p>Tanggal lahir: 24 Mei 2009</p>
    <p>Alamat: Sipolu polu</p>
    <p>Email: adityaidris535@gmail.com</p>
  </section>

  <section class="card">
    <h2>Pendidikan</h2>
    <p>Nama Sekolah: SMKN 2 PANYABUNGAN</p>
    <p>Kelas: XII TKJ²</p>
  </section>

  <section class="card">
    <h2>Hobi</h2>
    <ul>
      <li>Bermain game</li>
      <li>Menonton anime</li>
      <li>Mendengarkan musik</li>
    </ul>
  </section>

  <section class="card">
    <h2>Tentang Saya</h2>
    <p>
      Saya adalah seorang pelajar biasa tapi saya memiliki keingintahuan
      yang besar tentang teknologi dan ingin terus mengembangkan
      kemampuan diri.
    </p>
  </section>

</div>
</body>
</html>
  
