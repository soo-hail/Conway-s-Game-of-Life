
# Conway's Game of Life

Conway's Game of Life is a cellular automaton where a grid of cells evolves over discrete steps based on simple rules: cells are either "alive" or "dead," and their state in the next generation depends on the number of living neighbors they have. This game demonstrates how complex patterns and behaviors can emerge from simple initial conditions and rules.

### The Rules

The Game of Life is played on an infinite two-dimensional orthogonal grid of square cells. Each cell has two possible states: alive or dead. The state of the grid evolves in steps, or generations, according to these rules:

- **Death(underpopulation)**: A live cell with fewer than two live neighbors dies.
- **Death(overpopulation)**: A live cell with more than three live neighbors dies.
- **Survival**: A live cell with two or three live neighbors stays alive.
- **Birth**: A dead cell with exactly three live neighbors becomes a live cell.

### Running the Game

1. **Installation**: Ensure Python 3.x is installed. Install Pygame using `pip install pygame`.
2. **Run**: Execute `python game_of_life.py` to start the simulation.
3. **Controls**: Use mouse clicks and keyboard shortcuts to interact with the simulation.

## Implementation Details

### Pygame Setup

- Initialize Pygame and define constants such as screen size (`WIDTH`, `HEIGHT`), cell size (`CELL_SIZE`), and frames per second (`FPS`).

### Grid and Cell Handling

- Use a set (`positions`) to represent live cells and functions to draw the grid (`draw_grid`) and get neighbors (`get_neigh`).

### Game Logic

- Implement rules for Conway's Game of Life in the `update_grid` function:
  - Any live cell with fewer than two live neighbors dies (underpopulation).
  - Any live cell with two or three live neighbors survives.
  - Any live cell with more than three live neighbors dies (overpopulation).
  - Any dead cell with exactly three live neighbors becomes alive (reproduction).

### User Interaction

- **Mouse Click**: Toggle cell state (alive or dead).
- **Spacebar**: Start/Pause simulation.
- **C(key)**: Clear the grid.
- **G(key)**: Generate a random starting pattern.







