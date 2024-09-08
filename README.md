# Sudoku Solver

## Description
Sudoku is becoming a well-liked past time for puzzle fans all around the world. However, many people find it time-consuming and difficult to solve Sudoku puzzles. Artificial intelligence (AI) has made great strides in solving Sudoku problems recently, offering a quick and easy method for doing so.

A Sudoku Solver web application built using Flask for the backend and a custom Python algorithm to validate and solve Sudoku puzzles. The application allows users to input Sudoku puzzles and returns a solved grid or indicates if the puzzle is unsolvable.

## Features

- Input Sudoku puzzles manually
- Validate Sudoku grids to ensure they follow the rules of Sudoku
- Solve Sudoku puzzles using a backtracking algorithm
- Web interface built with Flask, with easy-to-use forms to input puzzles

## Algorithm

The Sudoku solving algorithm uses backtracking to try all possible numbers in each empty cell. If a valid number is found, it moves on to the next empty cell. If the puzzle becomes unsolvable, it backtracks and tries the next possibility.

### Key Methods

- **solve():** Uses backtracking to solve the puzzle.
- **is_valid():** Checks if the current grid is valid by ensuring no duplicate numbers in rows, columns, and 3x3 subgrids.
- **RCB_lists():** Returns row, column, and subgrid lists for a given cell.
- **check_num():** Checks if a number can be placed at a specific position.

## Screenshots
