
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SECRET RELATIONSHIP</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#100e14;color:#f8f2f7;font-family:Arial,sans-serif}
header{padding:20px 7%;border-bottom:1px solid #40303e;display:flex;justify-content:space-between;align-items:center}
.logo{font-weight:900;letter-spacing:3px;color:#f2a9ca}
nav a{color:#ddd;text-decoration:none;margin-left:14px;font-size:13px}
.hero{padding:75px 7%;background:linear-gradient(110deg,#241522,#100e14 70%)}
.tag{color:#f2a9ca;letter-spacing:3px;font-size:12px}
h1{font-size:clamp(42px,9vw,82px);margin:20px 0;line-height:1}
h1 span{color:#f2a9ca}
p{color:#c8bfca;line-height:1.8}
button{padding:13px 18px;background:#f2a9ca;color:#241522;border:0;border-radius:5px;font-weight:bold;cursor:pointer}
section{padding:35px 7%}
h2{letter-spacing:1px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(145px,1fr));gap:13px}
.card{padding:17px;background:#1b1720;border:1px solid #40303e;border-radius:10px}
.card h3{margin-bottom:5px}
.role{font-size:11px;color:#f2a9ca;text-transform:uppercase;letter-spacing:1px}
.card p{font-size:13px}
.banner{border-left:3px solid #f2a9ca;padding:12px 18px;background:#1b1720}
footer{text-align:center;padding:30px;color:#948794;font-size:12px}
</style>
</head>
<body>
<header>
  <div class="logo">S.R. / AU</div>
  <nav>
    <a href="#story">STORY</a>
    <a href="#characters">CHARACTERS</a>
    <a href="#teams">TEAMS</a>
  </nav>
</header>

<div class="hero" id="story">
  <div class="tag">A SCHOOL ROMANCE AU</div>
  <h1>SECRET<br><span>RELATIONSHIP.</span></h1>
  <p>
    Mereka bertetangga. Mereka satu sekolah.<br>
    Mereka sudah bermusuhan selama tiga tahun.<br>
    Tapi bagaimana kalau kebencian itu menyimpan
    sesuatu yang tidak pernah mereka akui?
  </p>
  <button onclick="document.querySelector('#characters').scrollIntoView({behavior:'smooth'})">
    MEET THE CHARACTERS ↓
  </button>
</div>

<section>
  <div class="banner">
    <div class="role">THE MAIN STORY</div>
    <h2>Sean × Kean</h2>
    <p>
      Sean, siswa pintar dari kelas IPA, aktif di OSIS dan dikenal
      baik serta rendah hati. Kean, atlet basket dari kelas IPS,
      terkenal galak, bandel, songong, dan susah diajak akur.
      Sebagai tetangga sekaligus musuh selama tiga tahun,
      mereka selalu punya alasan untuk bertengkar.
      Namun, cerita mereka belum tentu sesederhana itu.
    </p>
  </div>
</section>

<section id="characters">
<h2>THE CHARACTERS</h2>
<p>Sepuluh orang, tiga lingkaran pertemanan, dan banyak rahasia.</p>
<div class="grid">
  <div class="card"><div class="role">OSIS · IPA</div><h3>Sean</h3><p>Pintar, baik, humble. Anak kepala sekolah dan direktur terkaya.</p></div>
  <div class="card"><div class="role">BASKET · IPS</div><h3>Kean</h3><p>Songong, bandel, toxic, galak, tegas. Atlet basket sekaligus musuh Sean.</p></div>
  <div class="card"><div class="role">BASKET</div><h3>James</h3><p>Teman Kean. Baik, rendah hati, dan anggota tim basket.</p></div>
  <div class="card"><div class="role">BASKET</div><h3>Martin</h3><p>Teman Kean yang baik dan humble.</p></div>
  <div class="card"><div class="role">OSIS</div><h3>Juhoon</h3><p>Teman Sean yang baik dan humble.</p></div>
  <div class="card"><div class="role">OSIS</div><h3>Sanghyeon</h3><p>Adik Kean. Petakilan, bawel, baik, dan humble.</p></div>
  <div class="card"><div class="role">BAND</div><h3>Sangwon</h3><p>Adik Sean. Dingin, tegas, dan anak band.</p></div>
  <div class="card"><div class="role">BAND</div><h3>Evan</h3><p>Teman Sangwon. Baik, humble, dan anak band.</p></div>
  <div class="card"><div class="role">KETUA OSIS</div><h3>Jungwon</h3><p>Ketua OSIS yang baik dan rendah hati.</p></div>
  <div class="card"><div class="role">BAND</div><h3>Suno</h3><p>Teman Sangwon. Tegas, dingin, dan anak band.</p></div>
</div>
</section>

<section id="teams">
<h2>THE CIRCLES</h2>
<div class="grid">
  <div class="card"><div class="role">01 · STUDENT COUNCIL</div><h3>OSIS</h3><p>Jungwon · Sean · Juhoon · Sanghyeon</p></div>
  <div class="card"><div class="role">02 · COURT</div><h3>BASKETBALL</h3><p>Kean · James · Martin</p></div>
  <div class="card"><div class="role">03 · MUSIC</div><h3>THE BAND</h3><p>Sangwon · Evan · Suno</p></div>
</div>
</section>

<section>
<h2>THE FAMILIES</h2>
<div class="grid">
  <div class="card"><h3>Jennie</h3><p>Ibu Sean dan Sangwon. Tegas, protektif, kepala sekolah.</p></div>
  <div class="card"><h3>Taehyung (V)</h3><p>Ayah Sean dan Sangwon. Tegas, protektif, direktur terkaya.</p></div>
  <div class="card"><h3>Lisa</h3><p>Ibu Kean dan Sanghyeon. Seleb gaul, aktif di media sosial, humble, dan girls banget.</p></div>
  <div class="card"><h3>Jungkook</h3><p>Ayah Kean dan Sanghyeon. Gaul, humble, dan baik.</p></div>
</div>
</section>

<footer>SECRET RELATIONSHIP · AN ORIGINAL AU UNIVERSE</footer>
</body>
</html>
# secret-relationship
Secret Relationship AU Website
