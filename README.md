# test
my first project
<!DOCTYPE html>
<html>
<head>
    <title>Snake Game - Weed Theme</title>
    <style>
        #game-board {
            width: 300px;
            height: 300px;
            border: 1px solid black;
            position: relative;
            background-color: #228B22; /* Green background for the "weed" theme */
        }
        .snake-part {
            width: 20px;
            height: 20px;
            background-color: #8B4513; /* Brown color for the snake */
            position: absolute;
        }
        #food {
            width: 20px;
            height: 20px;
            background-color: #FFD700; /* Gold color for the food */
            position: absolute;
        }
    </style>
</head>
<body>
    <div id="game-board"></div>
    <script>
        const gameBoard = document.getElementById("game-board");
        let snake = [{ x: 10, y: 10 }]; // Initial position of the snake
        let food = { x: 5, y: 5 }; // Initial position of the food
        let direction = "right"; // Initial direction of the snake

        // Rest of the JavaScript code to handle game logic
        // such as moving the snake, growing the snake when it eats food,
        // and ending the game when the snake collides with the wall or itself
    </script>
</body>
</html>
