<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Dice Game</title>

    <!-- style sheets -->
    <link rel="stylesheet" href="styles.css">

    <!-- fonts -->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Redressed&display=swap" rel="stylesheet">

    <!-- favicon -->
    <link rel="shortcut icon" href="res/three.png" type="image/png">
    
  </head>
  <body>

<!-- title -->
    <div class="title">
      <h1>Player X Wins</h1>
    </div>

<!-- dice -->
    <div class="game">
      <div class="">
        <h3>Player 1</h3>
        <h3>Player 2</h3>
      </div>
      <div class="">
        <img class="dice-one" src="res/one.png" alt="">
        <img class="dice-two" src="res/one.png" alt="">
      </div>
      <button class="roll-button" type="button" name="button">Roll</button>
    </div>

<!-- footer -->
    <div class="footer">
      <div class="counter">
        <p class="counter-one">Player One: 0</p>
        <p class="counter-two">Player Two: 0</p>
      </div>

      <p class="end">Karl's Dice Game</p>
    </div>

    <script src="index.js" charset="utf-8"></script>
  </body>
</html>