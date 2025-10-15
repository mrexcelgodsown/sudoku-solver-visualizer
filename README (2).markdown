# Sudoku Solver Visualizer

A world-class, interactive web application to visualize a backtracking algorithm solving Sudoku puzzles. Built with Tailwind CSS for a modern, responsive design and JavaScript for solver logic.

## Features
- **Interactive Sudoku Board**: Input custom puzzles or load a sample.
- **Backtracking Visualization**: Animated solving process with cell highlights.
- **Responsive Design**: Sleek UI with dark/light theme toggle, gradients, and hover effects.
- **Real-Time Feedback**: Info panel shows solver status (e.g., "Solved!" or "Invalid puzzle").
- **Clean Code**: Modular JavaScript with clear solver logic.

## Demo
Try it live at [https://your-username.github.io/sudoku-solver-visualizer](https://your-username.github.io/sudoku-solver-visualizer).

![Demo GIF](assets/demo.gif)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver-visualizer.git
   ```
2. Open `index.html` in a modern browser (no server required).

## Usage
1. Enter numbers (1–9) in the grid or click "Load Sample" for a test puzzle.
2. Click "Solve" to watch the backtracking animation.
3. Use "Reset" to clear the board or "Toggle Theme" for dark/light mode.
4. Invalid puzzles are highlighted with an error message.

## Tech Stack
- **Frontend**: HTML, JavaScript
- **Styling**: Tailwind CSS (responsive, modern design)
- **Fonts**: Inter (via Tailwind)

## Algorithm Complexity
- Backtracking Solver: O(9^m) where m is the number of empty cells (worst case).
- Validation: O(1) per cell check.

## Future Enhancements
- Add puzzle generator for random boards.
- Implement difficulty levels.
- Support hints or partial solving.

## License
MIT License