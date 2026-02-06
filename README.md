<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ucapan Terima Kasih</title>

<style>
body{
    margin:0;
    font-family:Segoe UI, Arial, sans-serif;
    background:linear-gradient(135deg,#667eea,#764ba2);
    color:white;
}
.section{
    min-height:100vh;
    padding:40px 20px;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}
.card{
    max-width:800px;
    background:rgba(0,0,0,.35);
    padding:30px;
    border-radius:20px;
}
img{
    width:100%;
    max-width:280px;
    border-radius:20px;
    margin-bottom:20px;
}
p{
    line-height:1.7;
    text-align:justify;
}
button{
    margin-top:25px;
    padding:12px 25px;
    border:none;
    border-radius:30px;
    background:#ffd369;
    font-size:16px;
    cursor:pointer;
}
.footer{
    margin-top:20px;
    font-style:italic;
}
</style>
</head>

<body>

<!-- MUSIK -->
<audio autoplay loop>
  <source src="musik.mp3" type="audio/mpeg">
</audio>

<!-- HALAMAN AWAL -->
<div class="section">
    <h1>Ucapan Terima Kasih</h1>
    <p>Komisi Pemuda Remaja GKJ Temon</p>

    <p><i>
        “Hendaklah kamu sehati sepikir,  
        dalam satu kasih, satu jiwa, satu tujuan.”
    </i><br><b>Filipi 2:2</b></p>

    <button onclick="document.getElementById('dinda').scrollIntoView({behavior:'smooth'})">
        ↓ Scroll ↓
    </button>
</div>

<!-- MBAK DINDA -->
<div class="section" id="dinda">
    <div class="card">
        <img src="foto-dinda.jpg">

        <h2>✨ Untuk Mbak Dinda</h2>

        <p>
        Terima kasih, Mbak Dinda, telah menjadi sosok paling dewasa di antara kami.
        Dengan kesabaran dan kebijaksanaanmu, Mbak Dinda hadir sebagai penengah
        di tengah berbagai perbedaan dan perselisihan, terutama saat kami
        membutuhkan arah dan ketenangan.
        </p>

        <p>
        Terima kasih telah menjadi warna yang tidak pernah pudar,
        hadir dengan kelembutan, senyum, dan tawa,
        bahkan ketika di baliknya ada luka, lelah,
        dan tekanan yang tidak selalu terlihat.
        </p>

        <p>
        Selamat melanjutkan pelayanan sebagai
        Ketua Komisi Pemuda dan Remaja GKJ Temon periode 2026–2029.
        Kiranya setiap amanah dijalani dengan hikmat
        dan dalam penyertaan Tuhan.
        </p>

        <div class="footer">
            Tuhan memberkati setiap langkah dan proses 🤍
        </div>

        <button onclick="document.getElementById('indra').scrollIntoView({behavior:'smooth'})">
            ↓ Lanjut ↓
        </button>
    </div>
</div>

<!-- INDRA -->
<div class="section" id="indra">
    <div class="card">
        <img src="foto-indra.jpg">

        <h2>✨ Untuk Indra</h2>

        <p>
        Terima kasih telah menjadi partner Ketua Komisi Pemuda Remaja GKJ Temon
        paling josjis abad ini—penuh cerita, kerja keras,
        dipaido-maido, ngeyel, tapi tetap jalan 😄
        </p>

        <p>
        Terima kasih telah menjadi teman dan bestie
        yang mantap pokokke.
        Maaf kalau aku sering menyebalkan—
        walaupun yang paling menyebalkan sebenarnya kamu juga 🤝
        </p>

        <p>
        Selamat melanjutkan pelayanan sebagai
        Koordinator Komisi Pendukung Ibadat GKJ Temon.
        Semangat kuliah di PJKR dan bersiap menjadi “Pak Indra”
        di tugas berikutnya.
        </p>

        <div class="footer">
            Tuhan memberkati perjalananmu 🙏
        </div>
    </div>
</div>

</body>
</html>
