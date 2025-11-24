<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mary De Lillo</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
<style>
/* Reset */
body, html { margin: 0; padding: 0; height: 100%; font-family: 'Montserrat', sans-serif; }

/* Splash screen */
#splash {
position: fixed;
top: 0; left: 0;
width: 100%; height: 100%;
background: #ff5a5f;
color: #fff;
display: flex;
justify-content: center;
align-items: center;
font-size: 28px;
font-weight: bold;
z-index: 9999;
transition: opacity 0.5s ease;
}

/* Pagina principale */
#main {
display: none;
text-align: center;
background: #f0f0f5;
min-height: 100vh;
padding-top: 50px;
}

img {
border-radius: 50%;
width: 160px;
box-shadow: 0 8px 20px rgba(0,0,0,0.2);
transition: transform 0.3s;
margin-bottom: 20px;
}
img:hover { transform: scale(1.05); }

h1 { font-size: 34px; margin: 10px 0; }
p { font-size: 18px; color: #555; margin-bottom: 50px; }

.button {
display: block;
margin: 12px auto;
width: 240px;
padding: 14px 0;
font-size: 17px;
font-weight: bold;
border-radius: 35px;
border: none;
color: #fff;
background: linear-gradient(135deg, #ff5a5f, #ff8a65);
text-decoration: none;
cursor: pointer;
transition: 0.3s;
}
.button:hover {
transform: translateY(-3px);
box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

/* Mobile */
@media (max-width: 400px) {
img { width: 130px; }
.button { width: 200px; font-size: 16px; }
}
</style>
</head>
<body>

<!-- Splash screen -->
<div id="splash">Ciao, benvenuto!</div>

<!-- Pagina principale -->
<div id="main">
<img src="foto.jpg" alt="Mary De Lillo">
<h1>Mary De Lillo</h1>
<p>Tutti i miei link ufficiali</p>

<a class="button" href="https://www.instagram.com/mary.delillo?igsh=NGg4MW9vMzZyanRt&utm_source=qr" target="_blank">Instagram</a>
<a class="button" href="https://www.tiktok.com/@marydelilloofficial?_r=1&_t=ZN-91fms8Tr71K" target="_blank">TikTok</a>
<a class="button" href="https://onlyfans.com/marydelillo" target="_blank">Contenuti esclusivi</a>
<a class="button" href="https://t.me/MaryDeLilloVirgo" target="_blank">Telegram</a>
</div>

<script>
// Mostra la pagina principale dopo 2.5 secondi
setTimeout(() => {
document.getElementById('splash').style.opacity = '0';
setTimeout(() => { document.getElementById('splash').style.display = 'none'; }, 500);
document.getElementById('main').style.display = 'block';
}, 2500);
</script>

</body>
</html>
