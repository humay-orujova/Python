# Game of life

This is a Python implementation of a cellular automaton based on Conway's Game of Life, with a slight modification to include diagonal neighbors for the evolution of cells. I developed this project as part of my university coursework, showcasing my ability to apply Python in simulations and algorithms. 

### Project Description

The Game of Life is a zero-player game where cells evolve over multiple steps according to a set of simple rules. In this simulation:

- Each cell is either alive (1) or dead (0).
- The grid evolves at each step based on the number of neighbors each cell has.

### Rules:

1. **Survival:** A cell remains alive if it has 2 or 3 live neighbors.
2. **Death:** A cell dies if it has fewer than 2 or more than 3 live neighbors.
3. **Reproduction:** A dead cell comes to life if it has exactly 3 live neighbors.

### Diagonal Neighbors:

In this implementation, cells interact with not only their immediate vertical and horizontal neighbors but also their diagonal neighbors.

### How It Works

- **Initialization:** A grid of size N×NN×N (100x100 by default) is randomly filled with live cells, each having a 40% chance of being alive.
- **Simulation:** The grid evolves for 200 steps, with a display of the grid at steps t=0,50,100,200t=0,50,100,200.
- **Visualization:** The grid at each step is visualized using Matplotlib, with black representing dead cells and white representing alive cells.
