<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Selamat Ulang Tahun!</title>
  <style>
    body {
      background-color: #ffe6f0;
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
    }
    h1 {
      color: #e60073;
      margin-top: 30px;
      animation: blink 1s infinite;
    }
    @keyframes blink {
      0%, 100% {opacity: 1;}
      50% {opacity: 0;}
    }
    img {
      width: 300px;
      border-radius: 20px;
      margin: 20px 0;
    }
    marquee {
      color: #cc0066;
      font-size: 20px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h1>Selamat Ulang Tahun!</h1>

  <img src="foto.jpg" alt="Foto Ulang Tahun">

  <marquee>Semoga panjang umur, sehat selalu, dan bahagia selalu!</marquee>

  <audio autoplay loop>
    <source src="lagu.mp3" type="audio/mpeg">
    Browser kamu tidak mendukung audio.
  </audio>

</body>
</html>
