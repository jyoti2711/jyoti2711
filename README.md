Creating a tic-tac-toe game is a fun way to practice JavaScript! Here's a simple example of a tic-tac-toe game implemented in HTML, CSS, and JavaScript:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tic Tac Toe</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Tic Tac Toe</h1>
    <div id="game-board">
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
      <div class="cell" data-cell></div>
    </div>
    <button id="restartButton">Restart Game</button>
  </div>
  <script src="script.js"></script>
</body>
</html>
