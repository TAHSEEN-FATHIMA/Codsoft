 # Tic-Tac-Toe Game (with AI)

This project implements a graphical version of the classic Tic-Tac-Toe game using Python and OpenCV. The game supports two modes: Player vs Player and Player vs Computer. The computer opponent uses the Minimax algorithm to make intelligent moves, offering a challenging experience for the player.

## Features

- **Player vs Player** mode: Play with a friend on the same machine.
- **Player vs Computer** mode: Play against an AI that uses the Minimax algorithm to make decisions.
- **Reset and Exit**: Reset the game or exit at any time using the keyboard.
- **Game Status**: Displays whose turn it is, and notifies when a player wins or if the game ends in a draw.
- **Intuitive Interface**: The game is displayed using OpenCV, providing real-time visual feedback.
  
 The game window will appear. You can interact with the game using the following controls:
   - **Mouse Click**: Click on an empty square to place your move.
   - **Space**: Toggle between Player vs Player or Player vs Computer mode.
   - **R**: Reset the game.
   - **Esc**: Exit the game.

## Game Flow

1. **Player vs Player Mode**: Both players take turns to place their markers ('X' or 'O') on the grid. The game ends when one player wins or if there is a draw.
2. **Player vs Computer Mode**: The player competes against an AI opponent. The AI uses the Minimax algorithm to evaluate the game board and choose the best possible move. The AI's moves are shown automatically after the player's turn.

## How It Works

- The game board consists of 9 blocks, arranged in a 3x3 grid.
- The player and computer take turns placing their markers ('X' for Player 1, 'O' for Player 2 or AI).
- The game checks for a win condition after every move by verifying rows, columns, and diagonals.
- If the board is filled without a winner, the game ends in a draw.

## Minimax Algorithm

The AI's decision-making process is based on the **Minimax algorithm**, which evaluates all possible moves and selects the one that maximizes its chances of winning while minimizing the player's chances. The algorithm recursively simulates the game to a certain depth, scoring each possible move based on whether it results in a win, loss, or draw.

## Acknowledgements

- The game uses **OpenCV** for rendering the graphical interface.
- The AI logic is implemented using the **Minimax algorithm** to provide intelligent gameplay for the computer.
