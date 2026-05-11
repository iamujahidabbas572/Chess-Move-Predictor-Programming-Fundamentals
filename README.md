# Chess Move Predictor and "Save the King" Game

A C++ console-based application that allows users to visualize all possible next moves for various chess pieces on an 8x8 chessboard. Additionally, it features an interactive "Save the King" mini-game where the player must move their King to evade attacks from an enemy piece.

## Features

* **Move Prediction**: Select a chess piece and its starting position to see all valid next moves displayed on the console.
* **Supported Pieces**: 
  * King
  * Queen
  * Rook
  * Bishop
  * Knight
* **Visual Representation**: The chessboard and the valid moves are displayed using console text coloring for clear visualization.
* **"Save the King" Mini-game**: Test your skills by evading attacks from an enemy Queen, Rook, Bishop, or Knight.

## Getting Started

### Prerequisites

* A C++ compiler (e.g., GCC, Clang, or MSVC)
* Windows OS (due to the usage of `<Windows.h>` for console text colors)

### Compilation and Execution

1. Open your terminal or command prompt.
2. Navigate to the directory containing `Chess.cpp`.
3. Compile the code using your preferred C++ compiler. For example, using `g++`:
   ```bash
   g++ Chess.cpp -o Chess
   ```
4. Run the compiled executable:
   ```bash
   Chess.exe
   ```

## Usage

1. Upon running the program, you will be prompted to select a chess piece from a menu.
2. Enter the desired row (1-8) and column (1-8) for the starting position of the selected piece.
3. The console will display the chessboard with the piece's initial position and highlight all possible next moves.
4. After reviewing the moves, you can choose to play the "Save the King" mini-game.

## Contributors

* Mujahid Abbas (22i-1969)
* Talha Kayani (22i-1914)
