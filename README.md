<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mary De Lillo</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
<style>
/* Reset e font */
body, html { margin: 0; padding: 0; height: 100%; font-family: 'Montserrat', sans-serif; }

/* Splash screen */
#splash {
position: fixed;
top: 0; left: 0;
width: 100%; height: 100%;
background: linear-gradient(135deg, #ff5a5f, #ff8a65);
color: #fff;
display: flex;
justify-content: center;
align-items: center;
font-size: 32px;
font-weight: bold;
z-index: 9999;
transition: opacity 0.5s ease;
}

/* Pagina principale */
#main {
display: none;
text-align: center;
background: linear-gradient(to bottom, #f0f0f5, #e0dfee);
min-height: 100vh;
padding-top: 50px;
}

img {
border-radius: 50%;
width: 160px;
box-shadow: 0 8px 20px rgba(0,0,0,0.2);
margin-bottom: 20px;
transition: transform 0.3s;
}
img:hover { transform: scale(1.05); }

h1 { font-size: 36px; margin: 10px 0; }
p { font-size: 18px; color: #555; margin-bottom: 50px; }

/* Pulsanti con animazione */
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
opacity: 0;
transform: translateY(20px);
animation: fadeInUp 0.6s forwards;
}
.button:nth-child(1) { animation-delay: 0.5s; }
.button:nth-child(2) { animation-delay: 0.8s; }
.button:nth-child(3) { animation-delay: 1.1s; }
.button:nth-child(4) { animation-delay: 1.4s; }

@keyframes fadeInUp {
to { opacity: 1; transform: translateY(0); }
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
<div id="splash">✨ Ciao, benvenuto! ✨</div>

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
