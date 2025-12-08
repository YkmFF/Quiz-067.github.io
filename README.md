<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Unblocked Game Launcher</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f7ff;
      text-align: center;
      margin-top: 40px;
    }
    #main {
      background: #fff;
      display: inline-block;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(0,0,0,0.12);
    }
    .url {
      margin-top: 20px;
      font-size: 1.1em;
      color: #4b7bec;
    }
    .score {
      font-size:2em;
      margin:20px;
    }
    #clickBtn {
      padding: 14px 40px;
      font-size: 1.2em;
      background: #70a1ff;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    #clickBtn:hover {
      background: #1e90ff;
    }
  </style>
</head>
<body>
  <div id="main">
    <h2>Unblocked Clicker Game</h2>
    <div class="score" id="score">Score: 0</div>
    <button id="clickBtn">Click Me!</button>
    <div class="url">
      🔗 Unblocked via: <a href="https://Quiz-67.github.io" target="_blank">Quiz-67.github.io</a>
    </div>
    <p style="margin-top:24px;color:gray;">
      This page lets you play simple games, unblocked at school!<br>
      Add more games below or modify code for more fun.<br>
      (Educational use only!)
    </p>
  </div>
  <script>
    let score = 0;
    const scoreEl = document.getElementById('score');
    document.getElementById('clickBtn').onclick = () => {
      score++;
      scoreEl.textContent = "Score: " + score;
    };
  </script>
</body>
</html># Quiz-67-.github.io