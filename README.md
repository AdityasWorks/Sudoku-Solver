# Sudoku Solver

This Python script solves a Sudoku puzzle using a backtracking algorithm.

## Example Sudoku Board

```python
board = [
    [5, 3, 0, 0, 7, 0, 0, 0, 0],
    [6, 0, 0, 1, 9, 5, 0, 0, 0],
    [0, 9, 8, 0, 0, 0, 0, 6, 0],
    [8, 0, 0, 0, 6, 0, 0, 0, 3],
    [4, 0, 0, 8, 0, 3, 0, 0, 1],
    [7, 0, 0, 0, 2, 0, 0, 0, 6],
    [0, 6, 0, 0, 0, 0, 2, 8, 0],
    [0, 0, 0, 4, 1, 9, 0, 0, 5],
    [0, 0, 0, 0, 8, 0, 0, 7, 9]
]
```

## Functions
- Print_Board(bo): Prints the Sudoku board in a readable format.
- find_Empty(bo): Finds an empty cell (represented by 0) in the board.
- valid(bo, num, pos): Checks if placing a number num at position pos is valid according to Sudoku rules.
- solve(bo): Solves the Sudoku puzzle using backtracking.

## Usage
1. Clone Repository
```bash
git clone https://github.com/yourusername/sudoku-solver.git
```
2. Modify the "Board" variable
3. Run the Solver:
```bash
python Solver.py
```
