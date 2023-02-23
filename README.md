Sudoku Solver
=========

This is a Python program for solving a Sudoku puzzle.

**[Click Here!](www.pete-j-matthews.com/Sudoku-Solver)**

Description
-----------

The `solver.py` program uses a recursive algorithm to find the solution to a given Sudoku puzzle. It works by iterating through each empty cell in the puzzle and testing each possible number in that cell until a valid solution is found. If no solution can be found with the current set of numbers, the algorithm backtracks and tries a different number.

The program also includes functions for checking the validity of a given number in a given cell and for printing the puzzle board.

Getting Started
---------------

### Web App

Web app works best on chrome/edge and can take up to 15 seconds to solve. For optimal results and to watch algorithm in action, please follow the instructions to install locally.

#### Instructions
Click a box and hit the number on your keybaord to pencil in a number. To confirm that value press the ENTER key on that box. To delete a pencil in you can click DEL. Finally to solve the board press SPACE, sit back and watch the algorithm run.


### Prerequisites

-   Python 3.x

### Installation

To download the program, you can clone the repository from GitHub:

shellCopy code

`$ git clone https://github.com/Pete-J-Matthews/Sudoku-Solver.git`

### Usage

To execute the program, navigate to the directory containing `solver.py` or 'main.py' for the GUI and run:

`$ python3 solver.py`

This will run the program and solve the Sudoku puzzle contained within the `test_board` variable in the file.



Authors
-------

-   Pete Matthews

Version History
---------------

-   0.1
    -   Initial release

License
-------

This project is licensed under the MIT License - see the [LICENSE.md].

Acknowledgments
---------------

-   This program was inspired by a similar program by Tech With Tim.
-   The Sudoku puzzle used in the `test_board` variable was taken from SudokuWiki.org.

