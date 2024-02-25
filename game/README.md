# Conway's Game of Life

## Introduction
Conway's Game of Life is a cellular automaton devised by mathematician John Conway in 1970. It's a zero-player game, meaning that its evolution is determined by its initial state, with no further input. The game is played on a grid of cells, where each cell can be alive or dead.

## Rules
1. **Underpopulation:** A living cell with fewer than two live neighbors dies.
2. **Survival:** A living cell with two or three live neighbors survives to the next generation.
3. **Overpopulation:** A living cell with more than three live neighbors dies.
4. **Reproduction:** A dead cell with exactly three live neighbors becomes a live cell.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/marangaa/conways_game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd conways_game
   ```

3. Run the game:
   ```bash
   python game_of_life.py
   ```

## Customization
- Adjust the initial state in the `initial_state.txt` file. Use 'O' for live cells and '.' for dead cells.
- Modify the grid size, generations, or any other parameters in the `game_of_life.py` file.

## Controls
- Press `Enter` to start the simulation.
- Press `Ctrl+C` to stop the simulation.

## Dependencies
- Python 3.x

## Contributing
Feel free to contribute by opening issues or submitting pull requests. Your feedback and enhancements are welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Have fun exploring the fascinating world of Conway's Game of Life!