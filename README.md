<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROCK PAPER SCISSORS GAME</title>
    <link rel="stylesheet" href="game.css" />
</head>
<body>
    <h1>ROCK PAPER SCISSORS GAME</h1>
    <div class="choices" >
        <div class="choice" id="rock">
      <img src="./image/rock.png" alt="">
      </div>
      <div class="choice" id="paper">
        <img src="./image/paper.png" alt="">
        </div>
        <div class="choice" id="scisser">
            <img src="./image/scissors.png" alt="">
            </div>
    </div>
    <div class="scoreboard">
          <div class="score1">
                <p id="you">0</p>
                <p>user</p>
          </div>
          <div class="score2">
                <p id="comp">0</p>
                <p>computer</p>
          </div>
    </div>
    <div class="messages">
        <p id="message" >
            play your move
        </p>
    </div>
    <script src="game.js" ></script>

</body>
</html>
