<html lang="ru">
<head>
  <meta charset="UTF-8">
  <style>
    @font-face {
      font-family: 'Wide Latin';
      src: local('Wide Latin'), url('https://fonts.cdnfonts.com/s/14565/WideLatin.woff') format('woff');
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Wide Latin', sans-serif;
    }

    html, body {
      height: 100%;
      width: 100%;
      overflow: hidden;
    }

    body {
      background: url('6666.png') no-repeat center center fixed;
      background-size: cover;
      transform: scaleY(-1);
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      backdrop-filter: blur(8px);
      background: rgba(0, 0, 0, 0.3);
      z-index: 0;
    }

    .texture {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background: url('https://www.transparenttextures.com/patterns/asfalt-light.png') repeat;
      opacity: 0.08;
      z-index: 1;
      pointer-events: none;
    }

    .content {
      transform: scaleY(-1);
      z-index: 2;
      position: relative;
      display: flex;
      flex-direction: column;
      align-items: center;
      color: white;
      text-align: center;
    }

    h1 {
      font-size: 5rem;
      text-shadow: 3px 3px 10px black;
      margin-bottom: 40px;
    }

    .order-note {
      font-size: 1.3rem;
      margin-bottom: 25px;
      letter-spacing: 2px;
      color: #fff;
      text-shadow:
        0 0 5px #fff,
        0 0 10px #fff,
        0 0 20px #fff,
        0 0 40px #fff;
    }

    .link {
      font-size: 1.2rem;
      color: white;
      text-decoration: none;
      padding: 14px 30px;
      margin: 12px 0;
      background: rgba(255, 255, 255, 0.1);
      display: inline-block;
      transition: background 0.3s ease;
      letter-spacing: 2px;
    }

    .link:hover {
      background: rgba(255, 255, 255, 0.25);
    }
  </style>
</head>
<body>

  <div class="overlay"></div>
  <div class="texture"></div>

  <div class="content">
   

    <div class="order-note">ДЛЯ ЗАКАЗА ШМОТОК ПИСАТЬ:</div>

    <a class="link" href="https://www.instagram.com/thug_lab_shop?igsh=dWxjdGFxNWtvdzF6" target="_blank">
      INSTAGRAM
    </a>

    <a class="link" href="https://t.me/thug_lab_petro" target="_blank">
      TELEGRAM
    </a>
  </div>

</body>
</html>
