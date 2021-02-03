
Sudoku Solver
This is a fairly simple Sudoku solver written in C. The backtracking loop is compact, it is kind of generic to many backtracking problems I believe. There is a matrix that stores the numbers, and there are redundant structures for rows, columns, and the nine sub-squares that maintain bit masks. They allow the program to check stuff using bitwise operators, which proved to be a fast approach compared to other options. Other than that, the program is not very smart, just brute force backtracking with the obvious optimizations. The program receives the square as a series of numbers of three digits. Each argument represents one of the known numbers in the Sudoku and is entered as row-col-number, where row and col are 1-based.
