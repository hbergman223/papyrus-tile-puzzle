# Tile Game

This is a simple grid-based game created using Python and the Pygame library. In the game, the player navigates through a grid of colorful tiles, each with different effects. The objective is to reach the black square without stepping on obstacles or encountering dangerous tiles.

## Features

- **Grid-Based Movement:** Move the player through a 10x10 grid using the arrow keys.
- **Tile Types:** Each tile has a different effect on the player, including walls, monsters, and electric tiles.
- **Randomized Grid:** The game generates a random grid with various tile types.
- **Victory Condition:** Reach the black square to win the game.
- **Obstacles and Hazards:** Certain tiles (e.g., wall, electric, piranhas) block or harm the player.

## Installation

To run this game, you need Python and the Pygame library installed. Follow the steps below to set it up:

1. Clone this repository or download the game files.
2. Install Python if you don't have it already. You can download it from [python.org](https://www.python.org/downloads/).
3. Install Pygame:
    ```bash
    pip install pygame
    ```

## Running the Game

1. Navigate to the project directory in your terminal.
2. Run the game script:
    ```bash
    python tile_game.py
    ```

The game window will open, and you can start playing!

## Controls

- **Arrow Keys**: Move the player around the grid.
- **Objective**: Reach the black square to win. Avoid stepping on dangerous tiles.

## Game Logic

- **Tiles**:
  - **Red (R)**: Wall - blocks movement.
  - **Green (G)**: Monster - blocks movement.
  - **Yellow (Y)**: Electric - blocks movement.
  - **Orange (O)**: Orange - allows movement and gives a special "oranges" smell.
  - **Purple (P)**: Purple - allows movement and gives a special "lemons" smell.
  - **Blue (B)**: Water - blocks movement unless you have the "oranges" smell.
  - **Pink (Pi)**: Start or Goal position.
  - **Black**: The goal tile, which the player must reach to win.

## Acknowledgements

- Pygame: The game uses the [Pygame library](https://www.pygame.org/), which makes it easy to create games in Python.
- Random module: Used to randomly generate the grid and the black square position.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

***Made with ChatGPT (no affiliation) because am lazy***
