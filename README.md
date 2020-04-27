# N-Queens-With-Obstacles
An upgraded version of the traditional N Queens problem. Obstacles are added to the game board, preventing Queens from attacking each other. For example:

0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0

0 0 0 9 0 0 0 0

0 0 0 0 1 0 0 0

0 0 0 0 0 9 0 0

0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0

0 0 0 0 0 0 0 0

Note: Obstacle = integer 1. Empty Spot = integer 0. Queen = integer 9

Without the obstacle, the two queens can attack each other, making the placement invalid. However, with the obstacle, two queens can no longer attack each other diagonally, and thus we have a valid placement. Similar for row attack and column attack.

The solver uses a recursive backtracking strategy and prints out all possible solution sets.
