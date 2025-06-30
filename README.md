# Dr-Kevin-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aviator Game Clone</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="container">
    <h1>Aviator Game Clone</h1>
    <p>Balance: <span id="balance">1000</span> Coins</p>

    <div class="game-display">
      <h2 id="multiplier">1.00x</h2>
    </div>

    <input type="number" id="betAmount" value="10" min="1"/>
    <button id="betBtn">Place Bet</button>
    <button id="cashoutBtn" disabled>Cash Out</button>

    <p id="status"></p>
  </div>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background: #121212;
  color: white;
  text-align: center;
  padding: 30px;
}

.container {
  max-width: 400px;
  margin: auto;
  background: #1e1e1e;
  padding: 20px;
  border-radius: 10px;
}

.game-display {
  margin: 20px 0;
  font-size: 2em;
  color: #ff3366;
}

input, button {
  margin: 10px;
  padding: 10px;
  font-size: 1em;
}

button:disabled {
  background: #888;
  color: #333;
}
