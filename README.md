# Sudoku-Solver
A non-random based algorithm to solve a 9x9 sudoku puzzle.

# Language Used
Python

# How to use:
1. In a text file, follow the format below. An underscore '_' reperesents a blank input for the puzzle.
   
_ _ 9 | 2 _ 3 | 8 _ _
_ _ _ | _ _ 9 | _ _ _
4 _ 8 | 6 _ 5 | 1 _ 3
------+-------+------
1 _ 2 | _ _ _ | 9 _ 4
_ _ _ | _ _ _ | _ _ _
8 _ 3 | _ _ _ | 5 _ 2
------+-------+------
9 _ 6 | 5 _ 2 | 3 _ 7
_ _ 1 | _ _ _ | _ _ _
_ _ 5 | 4 _ 8 | 6 _ _

2. Name the text file with the format {name}.txt
3. In the notebook, change the code on the third cell. # f = open("**{name}.txt**","r")
4. Run the code.

# Todo:
Scalability on more complex sudoku puzzles, current version does not consider case 1.4, 2.1-4

# Solving references:
https://www.conceptispuzzles.com/index.aspx?uri=puzzle/sudoku/techniques
