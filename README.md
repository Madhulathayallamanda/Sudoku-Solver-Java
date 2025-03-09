# Sudoku Solver in Java

This is a simple Java-based Sudoku solver using the backtracking algorithm. The program takes an unsolved 9x9 Sudoku puzzle as input and finds a valid solution efficiently.

## Features

- Solves any valid 9x9 Sudoku puzzle using recursion and backtracking.
- Simple, optimized, and easy to understand.
- Easily customizable to solve different Sudoku grids.

## How to Run

1. **Clone the repository** (if you haven't already):
   ```sh
   git clone https://github.com/your-username/Sudoku-Solver-Java.git

2.Navigate to the project directory
   cd Sudoku-Solver-Java

3. Compile the Java program:
  javac SudokuSolver.java

4. Run the program:
   java SudokuSolver

## Example Input:

Given the following Sudoku puzzle:
5 3 0  0 7 0  0 0 0
6 0 0  1 9 5  0 0 0
0 9 8  0 0 0  0 6 0
8 0 0  0 6 0  0 0 3
4 0 0  8 0 3  0 0 1
7 0 0  0 2 0  0 0 6
0 6 0  0 0 0  2 8 0
0 0 0  4 1 9  0 0 5
0 0 0  0 8 0  0 7 9

Example Output:
The solver will output the solved puzzle:
5 3 4  6 7 8  9 1 2
6 7 2  1 9 5  3 4 8
1 9 8  3 4 2  5 6 7
8 5 9  7 6 1  4 2 3
4 2 6  8 5 3  7 9 1
7 1 3  9 2 4  8 5 6
9 6 1  5 3 7  2 8 4
2 8 7  4 1 9  6 3 5
3 4 5  2 8 6  1 7 9
