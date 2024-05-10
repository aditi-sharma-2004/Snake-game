# Snake Game

This is a simple implementation of the classic Snake Game using HTML5 Canvas and JavaScript.

## Table of Contents
- [Introduction](#introduction)
- [How to Play](#how-to-play)
- [Features](#features)
- [Code Explanation](#code-explanation)
- [License](#license)

## Introduction
The Snake Game is a classic arcade game where the player controls a snake that moves around the screen, eating food to grow longer. The game ends if the snake collides with the walls or itself.

## How to Play
- Use the arrow keys on your keyboard to control the direction of the snake.
- The snake will continuously move in the direction specified by the last arrow key pressed.
- The goal is to eat as much food as possible without colliding with the walls or the snake itself.
- Each time the snake eats food, it grows longer.
- The game ends when the snake collides with the walls or itself.
- If you need a hint on the next best move, you can click the "Get Hint" button.

## Features
- Simple and intuitive controls using arrow keys.
- Random generation of food on the canvas.
- Collision detection with walls and snake's body.
- AI agent provides hints on the next best move.
- Responsive design for different screen sizes.

## Code Explanation
- The game is built using HTML5 `<canvas>` element for rendering graphics.
- JavaScript is used for game logic, including controlling the snake's movement, detecting collisions, and providing hints.
- The game loop (`setInterval(draw, 100)`) continuously updates the game state and redraws the canvas.
- The `suggestMove()` function calculates the next best move for the snake to reach the food.
- The `displayHint()` function shows the hint to the player when the "Get Hint" button is clicked.

## License
This project is licensed under the [MIT License](LICENSE).

