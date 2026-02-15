<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Virtual Valentine Flower 💖</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <h1>Untuk Kamu 💌</h1>
    <p>Klik bunga ini yaa 🌹</p>

    <div class="flower" onclick="showMessage()">
      <div class="petal petal1"></div>
      <div class="petal petal2"></div>
      <div class="petal petal3"></div>
      <div class="petal petal4"></div>
      <div class="center"></div>
      <div class="stem"></div>
    </div>

    <div id="message" class="hidden">
      <h2>Happy Valentine's Day ❤️</h2>
      <p>Semoga harimu seindah bunga ini 🌸</p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
