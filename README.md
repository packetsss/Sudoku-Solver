# Sudoku-Solver

A Sudoku Solver using **Python** that solves any Sudoku puzzles in 2 seconds (95% of the puzzles are solved within 0.5 sec regardless of the difficulty).

<img src="https://github.com/packetsss/Sudoku-Solver/blob/main/sudoku.gif">

Check out my GUI demo video on Youtube: [Click me!](https://www.youtube.com/watch?v=I6yYPYTiE7c)

Due to large file restriction, you may NOW download the `.exe` version of the GUI (everything built in) in my <u>[google drive](https://drive.google.com/file/d/14FB2TLbyGtMjwN09txXWIW6_bbxqGOOw/view?usp=sharing) </u>(Anti-virus scan passed)

## Quick Start
```
# with gui
python Sudoku_gui_tkinter.py

# without gui (in terminal)
python Sudoku_solver.py
```
If you want to use a customized board, either add a line to ```puzzle1.txt``` following the nested list format, or add a line to ```User_data.txt``` and then use ```Sudoku_converter.py``` to convert that puzzle into the `puzzle1.txt`.

## Installation
`pip install numpy` (required)

`pip install tkinter` or `pip install pygame` (optional: if you wish to run the GUI)

Clone this repository (required)

You are all set!

## Performance
On the [hardest Sudoku in the world](https://www.telegraph.co.uk/news/science/science-news/9359579/Worlds-hardest-sudoku-can-you-crack-it.html):
`800000000003600000070090200050007000000045700000100030001000068008500010090000400`

The performance is below:

```
Solver:
[[8 1 2 7 5 3 6 4 9]
 [9 4 3 6 8 2 1 7 5]
 [6 7 5 4 9 1 2 8 3]
 [1 5 4 2 3 7 8 9 6]
 [3 6 9 8 4 5 7 2 1]
 [2 8 7 1 6 9 5 3 4]
 [5 2 1 9 7 4 3 6 8]
 [4 3 8 5 2 6 9 1 7]
 [7 9 6 3 1 8 4 5 2]]

Time consumed: 0.87877
Attempts: 32
```

