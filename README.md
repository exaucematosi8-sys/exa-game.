<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>EXA GAME</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      font-family: Arial, sans-serif;
      background:
        radial-gradient(circle at top, #172554, #050816 65%);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .container {
      width: 100%;
      max-width: 500px;
      text-align: center;
    }

    .logo {
      font-size: 42px;
      font-weight: 900;
      color: #00eaff;
      text-shadow:
        0 0 10px #00eaff,
        0 0 25px #0066ff;
      margin-bottom: 10px;
    }

    .welcome {
      font-size: 25px;
      font-weight: bold;
      margin-bottom: 35px;
    }

    .menu {
      display: flex;
      flex-direction: column;
      gap: 18px;
    }

    .menu-button {
      display: block;
      text-decoration: none;
      color: white;
      font-size: 22px;
      font-weight: bold;
      padding: 20px;
      border-radius: 18px;

      background: rgba(20, 30, 60, 0.9);
      border: 2px solid #00eaff;

      box-shadow:
        0 0 10px rgba(0, 234, 255, 0.4),
        inset 0 0 15px rgba(0, 234, 255, 0.08);

      transition: 0.25s;
    }

    .menu-button:hover {
      transform: scale(1.04);
      background: #00eaff;
      color: #050816;

      box-shadow:
        0 0 15px #00eaff,
        0 0 35px #0066ff;
    }

    .menu-button:active {
      transform: scale(0.97);
    }

    .footer {
      margin-top: 35px;
      font-size: 14px;
      color: #8ea3c7;
    }
  </style>
</head>

<body>

  <main class="container">

    <div class="logo">
      🎮 EXA GAME
    </div>

    <div class="welcome">
      Bienvenue Gamers 👋🔥
    </div>

    <div class="menu">

      <a class="menu-button" href="psp.html">
        🎮 PSP 🔥
      </a>

      <a class="menu-button" href="psvita.html">
        🎮 PS Vita 🔥
      </a>

      <a class="menu-button" href="mobile.html">
        🎮 Jeux Mobile 🔥
      </a>

    </div>

    <div class="footer">
      © 2026 EXA GAME — Gaming Zone 🎮
    </div>

  </main>

</body>
</html>
