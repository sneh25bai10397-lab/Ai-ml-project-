N-Queens Problem - README
Overview
The N-Queens problem is a classic backtracking problem where the goal is to place N queens on an N×N chessboard such that no two queens attack each other. This means no two queens share the same row, column, or diagonal.
Features
- Solves N-Queens for any input N
- Uses backtracking algorithm
- Displays all possible solutions
- Counts total number of valid solutions
Requirements
- Python 3.x
- No external libraries required
How to Run
1. Save the Python file.
2. Open terminal or command prompt.
3. Run the program using:
   python filename.py
4. Enter the number of queens when prompted.
How It Works
The program uses a backtracking approach:
- It places queens column by column.
- For each position, it checks if placing a queen is safe.
- If safe, it places the queen and moves to the next column.
- If not, it backtracks and tries another position.
Functions
initialize_table(n): Creates an empty chessboard.
check_valid(table, row, col, n): Checks if a queen can be placed safely.
replace_queens(table, col, n, solutions): Recursive backtracking function.
get_solutions(n): Returns all valid solutions.
print_result(solutions): Prints all solutions.
nqueens(): Main function to execute the program.
Example Output
For N = 4, the program will output all valid arrangements of 4 queens and display the total number of solutions.
