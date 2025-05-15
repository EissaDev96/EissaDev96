<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Shadow Moranch</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(to bottom, #0f0f0f, #1a1a1a);
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    .container {
      text-align: center;
      padding: 20px;
    }
    .title {
      font-size: 3rem;
      color: #8e44ad;
    }
    .tagline {
      font-size: 1.2rem;
      color: #ccc;
      margin-bottom: 30px;
    }
    .card {
      background-color: #111;
      border: 2px solid #8e44ad;
      border-radius: 20px;
      padding: 30px;
      width: 350px;
      box-shadow: 0 0 20px rgba(142, 68, 173, 0.6);
    }
    .pfp {
      width: 120px;
      border-radius: 50%;
      border: 3px solid #8e44ad;
      margin-bottom: 15px;
    }
    .links a {
      color: #8e44ad;
      text-decoration: none;
      margin: 0 10px;
      font-size: 1.1rem;
    }
    .ranks {
      margin-top: 20px;
      text-align: left;
    }
    .rank-item {
      margin-bottom: 8px;
    }
    .label {
      color: #aaa;
    }
    .value {
      color: #fff;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="title">The Shadow Moranch</h1>
    <p class="tagline">S-Rank Only | Shadows Obey My Code</p>

    <div class="card">
      <img class="pfp" src="https://cdn.discordapp.com/avatars/1332398330512408719/placeholder.png" alt="Profile Picture">
      <div class="links">
        <a href="https://github.com/EissaDev96" target="_blank">GitHub</a>
        <a href="https://discord.com/users/1332398330512408719" target="_blank">Discord</a>
      </div>
      <div class="ranks">
        <div class="rank-item"><span class="label">Discord Bots:</span> <span class="value">🟣 S</span></div>
        <div class="rank-item"><span class="label">Web Frontend:</span> <span class="value">🔵 A</span></div>
        <div class="rank-item"><span class="label">RP Leadership:</span> <span class="value">🟣 S+</span></div>
        <div class="rank-item"><span class="label">UI/UX:</span> <span class="value">🟡 B</span></div>
      </div>
    </div>
  </div>
</body>
</html>
