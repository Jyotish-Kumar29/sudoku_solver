# Sudoku Solver

This project is a web-based Sudoku Solver that allows users to input a Sudoku puzzle, solve it, and clear the board for a new puzzle. The project includes an HTML interface and a JavaScript solver.

## Features

- **Input Sudoku Puzzle**: Users can manually input Sudoku puzzles into a 9x9 grid.
- **Solve Puzzle**: The application can solve the given Sudoku puzzle and display the solution on the board.
- **Clear Board**: Users can clear the board to input a new puzzle.
- **Three Difficulty Levels**: Includes examples of easy, medium, and hard puzzles.

## Test It
https://jyotish-kumar29.github.io/sudoku_solver/ 

## Files

### index.html

This file contains the HTML structure of the Sudoku Solver. It includes a 9x9 table where users can input their Sudoku puzzle and buttons to solve the puzzle or clear the board.

### sudoku.js

This file contains the logic for solving the Sudoku puzzle. It defines a `SudokuSolver` object with the following methods:
- `solve(boardString)`: Solves the puzzle given as a string.
- `solveAndPrint(boardString)`: Solves the puzzle and prints the solved board to the console.
- `recursiveSolve(boardString)`: Recursively solves the puzzle.
- Other helper methods to validate the board and get possible values for empty cells.

## Usage

1. **Open `index.html`**: Open the `index.html` file in a web browser.
2. **Input Puzzle**: Enter the Sudoku puzzle into the grid. Each cell is editable.
3. **Solve Puzzle**: Click the "Solve!" button to solve the puzzle.
4. **Clear Board**: Click the "Clear board" button to clear the grid and input a new puzzle.

## Example Puzzles

You can use the following example puzzles to test the solver:

- **Easy Puzzle**: `1-58-2----9--764-52--4--819-19--73-6762-83-9-----61-5---76---3-43--2-5-16--3-89--`
- **Medium Puzzle**: `-3-5--8-45-42---1---8--9---79-8-61-3-----54---5------78-----7-2---7-46--61-3--5--`
- **Hard Puzzle**: `8----------36------7--9-2---5---7-------457-----1---3---1----68--85---1--9----4--`

To test these puzzles, paste the puzzle string into the first row of the grid and click the "Solve!" button.

## Development

To make changes to the Sudoku Solver, you can modify the `sudoku.js` file. The main logic for solving the puzzle is contained within the `SudokuSolver` object. The HTML structure and styles can be modified in the `index.html` file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

