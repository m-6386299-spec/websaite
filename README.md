<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>UUM Museum Audio Guide</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: linear-gradient(120deg, #002B7F, #003399);
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 1px;
    }

    header p {
      margin-top: 10px;
      font-size: 1.2em;
    }

    nav {
      background: #001B5E;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #FFD700;
    }

    .intro {
      text-align: center;
      margin: 40px auto;
      max-width: 800px;
      padding: 0 20px;
    }

    section {
      background: white;
      margin: 50px auto;
      max-width: 900px;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    section h2 {
      color: #002B7F;
    }

    section p {
      text-align: justify;
      line-height: 1.6;
    }

    audio {
      width: 100%;
      margin-top: 15px;
    }

    .back-top {
      display: inline-block;
      margin-top: 20px;
      background: #002B7F;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
      transition: background 0.3s, color 0.3s;
    }

    .back-top:hover {
      background: #FFD700;
      color: #001B5E;
    }

    footer {
      background: #001B5E;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>UUM Museum Audio Guide</h1>
    <p>Temui sejarah dan warisan UUM dengan panduan audio interaktif</p>
  </header>

  <nav>
    <a href="#home">Laman Utama</a>
  </nav>

  <div id="home" class="intro">
    <h2>Selamat Datang ke Muzium UUM</h2>
    <p>Laman ini membolehkan anda meneroka sejarah dan warisan Universiti Utara Malaysia dengan panduan audio interaktif. Skrol ke bawah untuk meneroka segmen pameran.</p>
  </div>

  <!-- Segmen 1 -->
  <section id="segmen1">
    <h2>Segmen 1: Sejarah UUM</h2>
    <p>Segmen ini memaparkan perjalanan penubuhan Universiti Utara Malaysia sejak tahun 1984. Dari kampus sementara di Jitra hingga ke kampus indah Sintok hari ini, UUM terus berkembang sebagai pusat kecemerlangan pengurusan.</p>
    <audio controls>
      <source src="audiosegmen1.mp3" type="audio/mpeg">
      Browser anda tidak menyokong audio.
    </audio>
    <a href="#home" class="back-top">⬆ Kembali ke atas</a>
  </section>

  <!-- Segmen 2 -->
  <section id="segmen2">
    <h2>Segmen 2: Inovasi dan Teknologi</h2>
    <p>Pameran ini menyoroti pelbagai inovasi yang dicipta oleh warga universiti dalam bidang teknologi dan penyelidikan, memperlihatkan kemajuan UUM dalam era digital.</p>
    <audio controls>
      <source src="audiosegmen2.mp3" type="audio/mpeg">
      Browser anda tidak menyokong audio.
    </audio>
    <a href="#home" class="back-top">⬆ Kembali ke atas</a>
  </section>

  <!-- Segmen 3 -->
  <section id="segmen3">
    <h2>Segmen 3: Budaya dan Warisan</h2>
    <p>Segmen ini mempersembahkan artifak dan tradisi yang menjadi simbol warisan warga universiti. Ia menghubungkan nilai budaya tempatan dengan identiti akademik UUM.</p>
    <audio controls>
      <source src="audiosegmen3.mp3" type="audio/mpeg">
      Browser anda tidak menyokong audio.
    </audio>
    <a href="#home" class="back-top">⬆ Kembali ke atas</a>
  </section>

  <!-- Segmen 4 -->
  <section id="segmen4">
    <h2>Segmen 4: Kecemerlangan Akademik</h2>
    <p>Segmen ini menonjolkan pelbagai pencapaian akademik, penyelidikan dan sumbangan ilmuwan UUM dalam membentuk masa depan pendidikan negara.</p>
    <audio controls>
      <source src="audiosegmen4.mp3" type="audio/mpeg">
      Browser anda tidak menyokong audio.
    </audio>
    <a href="#home" class="back-top">⬆ Kembali ke atas</a>
  </section>

  <footer>
    &copy; 2025 UUM Museum Audio Guide | Universiti Utara Malaysia
  </footer>

</body>
</html>
