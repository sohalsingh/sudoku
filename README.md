# sudoku

# Sudoku Game

This is a text-based implementation of the Sudoku game in Python. It allows players to solve Sudoku puzzles on the command line.

## How to Play

1. Run the Python script `sudoku.py`.
2. The initial Sudoku board will be displayed.
3. The empty cells are represented by `0`.
4. To solve the puzzle, enter the numbers from `1` to `9` in the empty cells.
5. The game will validate your moves and update the board accordingly.
6. Once you've filled all the cells correctly, the program will display the completed Sudoku board.
7. If there is no solution for the given board, a message stating "No solution exists" will be displayed.

## Example Gameplay

```
Welcome to Sudoku!
Here's the initial board:
-------------------------
5 3 0 | 0 7 0 | 0 0 0
6 0 0 | 1 9 5 | 0 0 0
0 9 8 | 0 0 0 | 0 6 0
- - - - - - - - - - - - -
8 0 0 | 0 6 0 | 0 0 3
4 0 0 | 8 0 3 | 0 0 1
7 0 0 | 0 2 0 | 0 0 6
- - - - - - - - - - - - -
0 6 0 | 0 0 0 | 2 8 0
0 0 0 | 4 1 9 | 0 0 5
0 0 0 | 0 8 0 | 0 7 9
-------------------------
Solution:
-------------------------
5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
- - - - - - - - - - - - -
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
- - - - - - - - - - - - -
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9
-------------------------
```

## Project Structure

The project consists of the following files:

- `sudoku.py`: The main Python script containing the game logic.
- `README.md`: This README file explaining the project.
- (Optional) Additional files or directories if you decide to expand the project.

## Dependencies

This project has no external dependencies. It is built using the Python programming language and uses only standard libraries.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project as per the terms of the license.

---

Feel free to customize this README file according to your specific project requirements and preferences.
