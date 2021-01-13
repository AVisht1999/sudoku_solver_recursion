# sudoku_solver_recursion
This project is a 9x9 sudoku solver program. 

To run:-

Note:	Uncomment lines 59 to 61 for custom input. 

> Compile sudoku.cpp or run sudoku.exe from prompt

> Enter custom sudoku as space seperated digits wit 0 for empty cell. 

> The solution found is displayed otherwise no solution message is shown. 

The program makes use of recursion at each cell to determine a correct solution. For each cell, if it is 0 (empty), numbers 1 to 9 are checked. If the check is passed, the function is then called recursively for each subsequent cell. If the check is failed, the number is incremented and checked again. If all of the numbers from 1 to 9 fail the check, no solution is possible. The process ends when no empty cells are left. 

