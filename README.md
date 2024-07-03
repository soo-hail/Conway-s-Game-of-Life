
# Conway's Game of Life

Conway's Game of Life is a cellular automaton where a grid of cells evolves over discrete steps based on simple rules: cells are either "alive" or "dead," and their state in the next generation depends on the number of living neighbors they have. This game demonstrates how complex patterns and behaviors can emerge from simple initial conditions and rules.

### The Rules

The Game of Life is played on an infinite two-dimensional orthogonal grid of square cells. Each cell has two possible states: alive or dead. The state of the grid evolves in steps, or generations, according to these rules:

- **Death(underpopulation)**: A live cell with fewer than two live neighbors dies.
- **Death(overpopulation)**: A live cell with more than three live neighbors dies.
- **Survival**: A live cell with two or three live neighbors stays alive.
- **Birth**: A dead cell with exactly three live neighbors becomes a live cell.

## Installation

To run this project, you need to have Python and Pygame installed on your system. You can install Pygame using `pip install pygame`.

## How to Run


