# Conway's Game of Life Simulation
# By Omar Waseem

This project is an implementation of Conway's Game of Life using Python, NumPy, and Matplotlib. It simulates how a grid of cells evolves over time based on a simple set of rules.

## Features

- Random initial grid generation with adjustable size and density.
- Visual representation of live and dead cells.
- Iterative updates based on standard Game of Life rules.
- Modular Python functions for initialization, updating, and visualization.

## Rules of the Game

1. Any live cell with 2 or 3 live neighbors survives.
2. Any dead cell with exactly 3 live neighbors becomes a live cell.
3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.

## Technologies Used

- Python 3
- NumPy – for efficient array and matrix operations.
- Matplotlib – for visualizing the grid of cells.

## How to Run

1. Clone this repository.
2. Open the notebook `The_Game_of_Life.ipynb`.
3. Run all cells in sequence to:
   - Initialize a grid.
   - Visualize the starting configuration.
   - Step through the simulation of life.

## Example Output

[Game of Life Example](https://upload.wikimedia.org/wikipedia/commons/e/e5/Gospers_glider_gun.gif)

## Credits

- Inspired by the original concept from mathematician John Conway.
- Developed as part of coursework for Data Management in Data Science at Rutgers University, by Prof. James Abello and Haoyang Zhang.

