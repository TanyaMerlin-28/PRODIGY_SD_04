# PRODIGY_SD_04
This project implements an automatic Sudoku Solver that takes an incomplete 9×9 Sudoku grid as input and fills in the missing numbers by following Sudoku rules. The program uses the Backtracking algorithm to explore possible number placements and efficiently find the correct solution.

SUDOKU SOLVER

📌 Project Overview

This project implements an automatic Sudoku Solver using the Backtracking algorithm.
The program takes an unsolved 9×9 Sudoku puzzle as input and fills in the missing numbers while strictly following Sudoku rules.

The solver automatically explores valid possibilities, backtracks when a wrong choice is made, and finally displays the correct completed Sudoku grid.

🎯 Problem Statement

Create a program that:

Accepts an incomplete Sudoku puzzle as input

Uses backtracking or a suitable algorithm

Solves the puzzle automatically

Displays the completed Sudoku grid as output

🧠 How the Solution Works

The solver uses a Backtracking approach, which works as follows:

Find an empty cell in the Sudoku grid

Try placing numbers from 1 to 9

Check if the number follows Sudoku rules:

No repetition in the same row

No repetition in the same column

No repetition in the same 3×3 subgrid

If valid, place the number and move to the next empty cell

If no number fits, backtrack (remove the previous number and try a different one)

Repeat until the puzzle is solved

This guarantees a correct solution if one exists.

📥 Input Description

The input is a 9×9 Sudoku grid

Filled cells contain numbers 1–9

Empty cells are represented using 0

Example Input:
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9

📤 Output Description

The output is the completed Sudoku grid

All Sudoku rules are satisfied

Example Output:
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9

🛠️ Technologies Used

Programming Language: Python
Algorithm: Backtracking
Environment: Command Line / Terminal

▶️ How to Run the Program

1.Clone the repository or download the file

2.Open a terminal or command prompt

3.Navigate to the project folder

4.Run the program using:
python sudoku_solver.py

🧪 Test Cases
Test Case	Description	Result
TC01	Valid incomplete Sudoku	Solved successfully
TC02	Already solved Sudoku	Returned same grid
TC03	Invalid Sudoku	No solution found
TC04	Empty grid	Generated a valid solution
📊 Input–Process–Output Model
Stage	Description
Input	Unsolved Sudoku grid (with 0s)
Process	Backtracking algorithm
Output	Completed Sudoku grid

🎓 Learning Outcomes

Understanding backtracking algorithms

Learning recursive problem solving

Improving logical and analytical thinking

Working with 2D arrays and constraints

🚀 Conclusion

This Sudoku Solver project demonstrates how backtracking can be used to solve complex constraint-based problems efficiently. It is a beginner-friendly project that strengthens algorithmic thinking and problem-solving skills.
