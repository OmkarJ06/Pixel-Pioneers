# Pixel-Pioneers

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz Obstacle Adventure</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <div id="start-screen">
            <h1>QUIZ OBSTACLE ADVENTURE</h1>
            <p>Collect keys, answer quizzes, and reach the door!</p>
            <button id="start-btn">START GAME</button>
        </div>

        <div id="game-screen" style="display: none;">
            <div id="level-display">Level: <span id="current-level">1</span>/5</div>
            <div id="keys-display">Keys: <span id="keys-count">0</span></div>
            <canvas id="game-canvas" width="800" height="400"></canvas>
        </div>

        <div id="quiz-screen" style="display: none;">
            <h2 id="quiz-question"></h2>
            <div id="quiz-options"></div>
            <div id="quiz-feedback"></div>
        </div>

        <div id="level-complete" style="display: none;">
            <h2>LEVEL COMPLETE!</h2>
            <p>You unlocked the next door!</p>
            <button id="next-level-btn">NEXT LEVEL</button>
        </div>

        <div id="game-over" style="display: none;">
            <h2>GAME OVER</h2>
            <p id="game-over-message"></p>
            <button id="restart-btn">PLAY AGAIN</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
