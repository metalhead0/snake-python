# Snake Game

This is a simple implementation of the classic Snake game using Python and the Pygame library.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. **Clone the repository** (if applicable) or download the project files.

2. **Install the Pygame library**:
    ```sh
    pip install pygame
    ```

## How to Run

1. **Navigate to the project directory**:
    ```sh
    cd /path/to/your/project
    ```

2. **Run the game**:
    ```sh
    python projekt.py
    ```

## Game Controls

- **Arrow Keys**: Control the direction of the snake (Up, Down, Left, Right)
- **ESC**: Exit the game

## Game Rules

- The snake moves continuously in the current direction.
- Use the arrow keys to change the direction of the snake.
- The snake grows in length each time it eats a fruit.
- The game ends if the snake collides with the walls or its own body.

## Code Overview

### Main Game Loop

The main game loop handles the following tasks:
- Processing user input (arrow keys to change direction)
- Updating the snake's position
- Checking for collisions (with walls or itself)
- Drawing the game elements (snake, fruit, score)
- Refreshing the game screen at a fixed frame rate

### Functions

- `show_score(choice, color, font, size)`: Displays the current score on the screen.
- `game_over()`: Displays the game over screen and the final score, then exits the game.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- This project uses the [Pygame](https://www.pygame.org/) library for game development.