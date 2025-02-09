# Snake Game 🐍

A classic **Snake Game** implemented in Python using the **Turtle module**. This game follows the traditional rules where the snake moves in four directions, eats food to grow, and avoids colliding with itself or the walls.

## Features ✨
- 🟢 **Snake Movement**: Move the snake using arrow keys (Up, Down, Left, Right).
- 🍎 **Food Mechanics**: The snake grows in size when it eats food, and the food respawns randomly.
- 🎯 **Scoring System**: Each time the snake eats food, the score increases.
- 🚧 **Collision Detection**:
  - If the snake hits the wall, the game ends.
  - If the snake collides with itself, the game ends.

## Files 📂

### `main.py`
- The main entry point for running the game.
- Sets up the game window and initializes the **Snake**, **Food**, and **Scoreboard** objects.
- Controls the game loop and detects collisions.

### `snake.py`
- Defines the **Snake** class.
- Manages the snake's movement, growth, and direction changes.

### `food.py`
- Defines the **Food** class.
- Generates food at random positions on the screen.

### `scoredboard.py`
- Defines the **Scoreboard** class.
- Handles score tracking and displays the **Game Over** message when the game ends.

## Installation & Running the Game 🚀

1. **Clone the Repository**:
   ```bash
 
