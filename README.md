# Minesweeper

This is a Python implementation of 2-D Minesweeper!

First clone the repo,

You start a game by running the script:
```
python3 Minesweeper.py
```
(If you do not edit the parameters in the script, the script will automatically initialize it to a 10x10 board, with 10 bombs)

Enter parameters in row,column format

Note that the inputs must be that the number of bombs is less than the total number of spaces (n^2).

In order to "dig" at a certain location, you type in the index of the row, then the column, separated by a comma (whitespace optional). The game "digs" recursively around that location if there are no bombs nearby.

You can continue digging until either you hit a bomb (which is game over) or you've successfully dug up all n-b non-bomb locations (which is victory)!

