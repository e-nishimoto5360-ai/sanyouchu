<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>サンヨウチュウってなに？</title>
  <style>
    body {
      margin: 0;
      font-family: "Rounded Mplus 1c", "Hiragino Maru Gothic ProN", Arial, sans-serif;
      background-color: #d6d3c4;
      color: #333;
    }

    /* 背景レイヤー（ゆっくり動く） */
    .bg {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 120%;
      background-image: url("trilobite_bg.png");
      background-repeat: no-repeat;
      background-position: center top;
      background-size: cover;
      z-index: -1;
      transform: translateY(0);
    }

    header {
      text-align: center;
      padding: 50px 20px;
    }

    header h1 {
      background: rgba(255, 255, 255, 0.85);
      display: inline-block;
      padding: 18px 32px;
      border-radius: 22px;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 22px;
      padding: 28px;
      box-shadow: 0 6px 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #6b7c4a;
    }

    .highlight {
      background-color: #f3f1e7;
      border-left: 6px solid #b5b07a;
      padding: 12px;
      border-radius: 8px;
      margin: 15px 0;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      background: rgba(255,255,255,0.7);
    }
  </style>
</head>
<body>

  <div class="bg" id="bg"></div>

  <header>
    <h1>サンヨウチュウってなに？</h1>
  </header>

  <section>
    <h2>サンヨウチュウのしょうたい</h2>
    <p>
      サンヨウチュウは、とてもむかしの海にすんでいた生きものです。
      名前のとおり、体が三つの部分に分かれているのが大きなとくちょうです。
    </p>
    <div class="highlight">
      約5億年以上前のカンブリア紀から生きていました。
    </div>
  </section>

  <section>
    <h2>どんな かたち？</h2>
    <p>
      サンヨウチュウの体は、あたま・むね・しっぽのような形に分かれています。
      かたい殻でおおわれていて、身を守ることができました。
    </p>
  </section>

  <section>
    <h2>なぜ 化石が たくさん 見つかるの？</h2>
    <p>
      サンヨウチュウは世界中の海にたくさんいて、
      殻がかたかったため、化石として残りやすかったのです。
    </p>

  </section>

  <section>
    <h2>どうして いなくなったの？</h2>
    <p>
      海の環境が大きく変わったことなどが原因で、
      サンヨウチュウは長い時間をかけて絶滅しました。
    </p>
  </section>

  <footer>
    サンヨウチュウ学習サイト
  </footer>

  <script>
    const bg = document.getElementById("bg");
    window.addEventListener("scroll", () => {
      bg.style.transform = `translateY(${window.scrollY * 0.3}px)`;
    });
  </script>

</body>
</html># sanyouchu
