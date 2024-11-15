# Sudoku-Solver
A non-random based algorithm to solve a 9x9 sudoku puzzle.

# Language Used
Python

# How to use:
1. In a text file, follow the format below. An underscore '_' reperesents a blank input for the puzzle.
   
9 6 _ | _ 1 _ | _ 3 _<br>
3 _ 2 | _ _ _ | 8 _ 4<br>
_ 7 _ | _ _ _ | _ 9 6<br>
------+-------+------<br>
_ _ _ | 3 _ 8 | _ _ _<br>
6 _ 9 | _ _ _ | _ 8 5<br>
_ _ _ | 4 _ 9 | _ _ _<br>
------+-------+------<br>
_ 2 _ | 5 8 4 | _ 6 _<br>
5 _ 8 | _ _ _ | 2 _ 7<br>
_ 4 _ | _ 9 _ | 3 5 _<br>


2. Name the text file with the format {name}.txt
3. In the notebook, change the code on the third cell. # f = open("**{name}.txt**","r")
4. Run the code.

# Todo:
Scalability on more complex sudoku puzzles, current version does not consider case 1.4, 2.1-4

# Solving references:
https://www.conceptispuzzles.com/index.aspx?uri=puzzle/sudoku/techniques
