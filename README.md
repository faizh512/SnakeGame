# Snake Game

This is a simple Snake Game built using Python's `tkinter` library. The player controls a snake to eat food, and for each piece of food the snake consumes, it grows longer. The game ends when the snake collides with the game boundaries or its own body.

## Features

- Classic Snake Game mechanics.
- Responsive controls using arrow keys.
- Score display.
- Game-over screen when the snake collides with the walls or itself.

## Getting Started

### Prerequisites

You need to have Python installed on your machine. You can download it from [here](https://www.python.org/downloads/).

### Installation

1. Clone the repository or download the source code.

    ```bash
    git clone https://github.com/yourusername/snake-game.git
    cd snake-game
    ```

2. Install the necessary dependencies. The game only requires Python's built-in `tkinter` library, which comes pre-installed with Python.

    For Linux users, if `tkinter` is not installed, you can install it with the following command:
    
    ```bash
    sudo apt-get install python3-tk
    ```

3. Run the game by executing the Python file.

    ```bash
    python snake_game.py
    ```

## How to Play

1. Use the arrow keys to control the direction of the snake:
    - Left arrow key: Move left.
    - Right arrow key: Move right.
    - Up arrow key: Move up.
    - Down arrow key: Move down.

2. The snake grows longer each time it eats food (red circle).
3. The game ends if the snake runs into the wall or its own body.
4. The score is displayed at the top, and it increases by 1 point each time the snake eats food.

## Game Logic

- The game is played on a canvas of size 700x700 pixels.
- The snake and food are drawn on a grid of 50x50 pixel blocks.
- The snake starts with 3 body parts.
- The speed of the game is set to 100 milliseconds between moves, which controls the difficulty.
- If the snake collides with the wall or itself, the game displays a "GAME OVER" message.

## Code Structure

- **Snake class:** Handles the creation of the snake and its movement.
- **Food class:** Handles the generation of food at random positions.
- **next_turn function:** Moves the snake in the current direction and checks for food consumption and collisions.
- **change_direction function:** Changes the direction of the snake based on user input.
- **check_collisions function:** Detects if the snake has collided with the game boundary or itself.
- **game_over function:** Displays the "GAME OVER" message when the snake dies.

## Screenshots

![Snake Game Screenshot](screenshot.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The game is inspired by the classic Snake game.
- Thanks to the Python community for the resources and tutorials on `tkinter`.

