# 0x05. N Queens

## Description
The "0x05. N Queens" project is a classic problem in computer science and mathematics, known for its application of the backtracking algorithm to place N non-attacking queens on an N×N chessboard. This README provides an overview of the project requirements, concepts needed, tasks, and additional resources to aid in completing the project successfully.

## Concepts Needed
### Backtracking Algorithms:
- Understanding how backtracking algorithms explore all potential solutions to a problem and backtrack when a solution cannot be completed.
- [Backtracking Introduction](https://www.geeksforgeeks.org/backtracking-algorithms/)
### Recursion:
- Utilizing recursive functions to implement backtracking algorithms.
- [Recursion in Python](https://realpython.com/python-thinking-recursively/)
### List Manipulations in Python:
- Creating and manipulating lists, especially to store the positions of queens on the board.
- [Python Lists](https://www.programiz.com/python-programming/list)
### Python Command Line Arguments:
- Handling command-line arguments with the `sys` module.
- [Command Line Arguments in Python](https://www.tutorialspoint.com/python/python_command_line_arguments.htm)

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All files interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.4.3)
- All files end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file at the root of the project folder is mandatory
- Code should use the PEP 8 style (version 1.7.*)
- All files must be executable

## Tasks
### 0. N queens (mandatory)
- Implement a program that solves the N queens problem.
- Usage: `nqueens N`
- If the user called the program with the wrong number of arguments, print `Usage: nqueens N`, followed by a new line, and exit with status 1.
- N must be an integer greater or equal to 4.
- If N is not an integer, print `N must be a number`, followed by a new line, and exit with status 1.
- If N is smaller than 4, print `N must be at least 4`, followed by a new line, and exit with status 1.
- Print every possible solution to the problem, one solution per line.
- You don’t have to print the solutions in a specific order.
- You are only allowed to import the `sys` module.

## Example Output
$ ./0-nqueens.py 4
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]


## Additional Resources
- [Mock Interview](https://www.byte-by-byte.com/mock-interview/)
- [N Queens Problem](https://en.wikipedia.org/wiki/Eight_queens_puzzle)
- [Backtracking Algorithm](https://www.geeksforgeeks.org/backtracking-algorithms/)
- [Recursion in Python](https://realpython.com/python-thinking-recursively/)
- [Python Lists](https://www.programiz.com/python-programming/list)
- [Command Line Arguments in Python](https://www.tutorialspoint.com/python/python_command_line_arguments.htm)

Feel free to explore these resources to enhance your understanding of the concepts and complete the project successfully.

