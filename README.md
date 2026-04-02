<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Soju ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      color: #fff;
      text-align: center;
    }
    .container {
      padding: 50px 20px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }
    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: auto;
    }
    .heart {
      font-size: 50px;
      animation: beat 1s infinite;
    }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    button {
      margin-top: 30px;
      padding: 15px 25px;
      border: none;
      border-radius: 30px;
      background: #fff;
      color: #ff4e50;
      font-size: 1em;
      cursor: pointer;
    }
    button:hover {
      background: #ffe6e6;
    }
    .hidden-message {
      display: none;
      margin-top: 20px;
      font-size: 1.3em;
    }
  </style>
</head>
<body>  <div class="container">
    <h1>Happy Birthday My Love 🎉</h1>
    <h2>Soju ❤️</h2>
    <div class="heart">❤️</div>
    <p>
      Dear Soju, 
      <br><br>
      On your special day, I just want to tell you how much you mean to me. 
      You are my happiness, my smile, and my everything. 💖
      <br><br>
      I am so lucky to have you in my life.
      <br><br>
      Forever yours,
      <br>
      Ayen 💕
    </p><button onclick="showMessage()">Click for Surprise 🎁</button>
<div class="hidden-message" id="message">
  I love you more than words can say ❤️
</div>

  </div>  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script></body>
</html>
