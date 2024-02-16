# Minesweeper-like Game

## Overview
This is a Minesweeper-like game written in C++. The game creates a fixed-size minefield where the player's goal is to flag all the mines without triggering any.

## Game Features
- Fixed-size minefield with a width of 5 and a height of 8.
- A total of 10 mines are randomly placed in the minefield.
- The game offers basic functionalities such as flagging mines, revealing cells, and checking for mines.
- Uses simple console input and output for gameplay interaction.

## How to Play
- The player inputs commands to interact with the minefield.
- Commands include:
  - 'fXY' to flag a cell as a mine (e.g., 'f12' flags the cell at row 1, column 2).
  - 'uXY' to unflag a cell.
  - 'rXY' to reveal a cell.
- The game continues until all mines are correctly flagged or a mine is revealed.

## Key Concepts Demonstrated
- Use of constants and variables to represent the game state.
- Modularity through functions such as `initField`, `setMine`, `isMine`, `reveal`, and `executeCmd`.
- Conditional logic to determine the game's progression and outcome.
- Handling user input through standard console I/O.

## Compilation and Execution
To compile and run this game:
```bash
g++ minesweeper_game.cpp -o minesweeper_game
./minesweeper_game
