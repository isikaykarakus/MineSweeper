# Minesweeper Solver Using SAT
## Course Information
This project is part of the course Knowledge Representation and Learning 2023-2024 taught by Prof. Roberto Confalonieri and Prof. Luciano Serafini.

## Project Description
Minesweeper is a classic puzzle game where mines are hidden in a grid of squares. The objective is to uncover all the cells that do not contain mines. The game provides clues in the form of numbers within revealed cells, indicating how many of the adjacent cells contain mines. The challenge is to use these clues to deduce the location of all the mines without triggering any.

This project leverages a SAT (Satisfiability) solver to systematically determine which cells are safe and which contain mines. SAT solvers are powerful tools that can decide the satisfiability of logical propositions, making them well-suited for solving Minesweeper puzzles.

## Features

- This project uses the SAT solver Minisat22 to evaluate the constraints and determine whether each hidden cell contains a mine or is safe.


## Requirements
- Python 3.x
- python-sat package
  
