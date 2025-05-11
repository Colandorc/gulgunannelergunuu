<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Anneler Günü Kutlu Olsun</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fff8f0;
      color: #333;
      text-align: center;
      padding: 40px;
    }
    h1 {
      font-size: 2.5em;
      color: #d63384;
    }
    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: auto;
    }
    .photo {
      margin: 20px 0;
    }
    .photo img {
      width: 300px;
      border-radius: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .music-button {
      margin-top: 30px;
      background: #d63384;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1em;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Anneler Günü Kutlu Olsun ❤️</h1>
  <p>Senin gibi bir kadının annesi olmak bir gurur kaynağıdır. Gülüşünün kaynağını biliyorum. 💐</p>

  <div class="photo">
    <img src="https://via.placeholder.com/300" alt="Anne ve Kız Fotoğrafı">
  </div>

  <button class="music-button" onclick="playMusic()">🎶 Müzik Çalsın</button>

  <audio id="music" src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3"></audio>

  <script>
    function playMusic() {
      document.getElementById('music').play();
    }
  </script>
</body>
</html>
