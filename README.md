<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mary De Lillo</title>
<style>
/* Sfondo e font */
body {
margin: 0;
padding: 0;
font-family: 'Helvetica Neue', Arial, sans-serif;
background: #fafafa;
color: #333;
text-align: center;
}

/* Foto profilo */
img {
border-radius: 50%;
width: 150px;
margin-top: 50px;
box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}

/* Titolo e sottotitolo */
h1 {
margin-top: 20px;
font-size: 32px;
letter-spacing: 1px;
}
p {
font-size: 18px;
color: #555;
margin-bottom: 40px;
}

/* Pulsanti */
button {
display: block;
width: 220px;
margin: 12px auto;
padding: 14px 0;
font-size: 16px;
cursor: pointer;
border-radius: 30px;
border: none;
background: linear-gradient(45deg, #ff5a5f, #ff8a65);
color: #fff;
font-weight: bold;
transition: 0.3s;
}
button:hover {
transform: translateY(-2px);
box-shadow: 0 6px 12px rgba(0,0,0,0.2);
}

/* Mobile */
@media (max-width: 400px) {
img { width: 120px; }
button { width: 180px; }
}
</style>
</head>
<body>

<!-- Foto profilo -->
<img src="foto.jpg" alt="Mary De Lillo">

<!-- Titolo -->
<h1>Mary De Lillo</h1>

<!-- Sottotitolo -->
<p>Tutti i miei link ufficiali</p>

<!-- Pulsanti -->
<button onclick="window.location.href='https://instagram.com/tuonome'">Instagram</button>
<button onclick="window.location.href='https://tiktok.com/tuonome'">TikTok</button>
<button onclick="window.location.href='https://twitter.com/tuonome'">Twitter</button>
<button onclick="window.location.href='https://onlyfans.com/tuonome'">Contenuti esclusivi</button>

</body>
</html>
