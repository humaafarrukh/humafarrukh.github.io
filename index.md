<!--  <p>
      Based on original 2048 game code <a href="http://gabrielecirulli.com" target="_blank">  By Gabriele Cirulli</a>.
      </p>  -->
     <p>
      Basado en <a href="https://itunes.apple.com/us/app/1024!/id823499224" target="_blank">1024</a> por Veewo Studio y conceptualmente similar a <a href="http://asherv.com/threes/" target="_blank">Threes</a> por Asher Vollmer.
     </p> 

<!DOCTYPE html>
  <html>
  <head>
    <meta charset="utf-8">
    <title>Sweet Cravings</title>

    <link href="style/main.css" rel="stylesheet" type="text/css">
    <link rel="icon" href="img/favicon.png" type="image/png" />

    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, target-densitydpi=160dpi, initial-scale=1.0, maximum-scale=1, user-scalable=no, minimal-ui">
  </head>
  <body>
    <div class="container">
      <div class="heading">
        <h1 class="title">Sweet Cravings </h1>
        <div class="scores-container">
          <div class="score-container">0</div>
          <div class="best-container">0</div>
        </div>
      </div>
      <p class="game-intro">Join the sweet treats to merge together  </p>

      <div class="game-container">
        <div class="game-message">
         
          <div class="lower">
           <a class="keep-playing-button">Continue Playing</a>
           <a class="retry-button">Restart Game</a>
         </div>
       </div>

       <div class="grid-container">
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
        <div class="grid-row">
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
          <div class="grid-cell"></div>
        </div>
      </div>

      <div class="tile-container">

      </div>
    </div>

   <p class="game-explanation">
      <strong class="important"> <strong>HOW TO PLAY</strong>: Use your arrow keys to move the tiles. When two tiles with the image touch, they merge into one!
       </p>
     
 <!--
       
      <p>
       2048 original por <a href="http://gabrielecirulli.com" target="_blank"> Gabriele Cirulli</a>.
      </p>
     <p>
    
  </p> -->
</div>

<script src="js/animframe_polyfill.js"></script>
<script src="js/keyboard_input_manager.js"></script>
<script src="js/html_actuator.js"></script>
<script src="js/grid.js"></script>
<script src="js/tile.js"></script>
<script src="js/local_score_manager.js"></script>
<script src="js/game_manager.js"></script>
<script src="js/application.js"></script>
</body>
</html>
