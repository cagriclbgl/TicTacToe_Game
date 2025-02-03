# Tic Tac Toe Game

## Overview
This is a simple console-based Tic Tac Toe game implemented in C#. The game allows two players to take turns and mark their respective choices on a 3x3 board until one of them wins or the game ends in a draw.

## Features
- Two-player game (Player 1: X, Player 2: O)
- Console-based user interface
- Automatic validation to prevent overwriting an already marked cell
- Simple win and draw detection

## Installation
### Prerequisites
- .NET SDK (for compiling and running the C# program)
- Any C# compatible IDE (e.g., Visual Studio, Visual Studio Code) or command line

### Steps
1. Clone this repository or download the source code.
   ```sh
   git clone https://github.com/cagriclbgl/TicTacToe_Game.git
   ```
2. Navigate to the project folder.
   ```sh
   cd TicTacToe_Game
   ```
3. Compile and run the program.
   ```sh
   dotnet run
   ```

## How to Play
1. The game starts by displaying the Tic Tac Toe board with numbered positions.
2. Players take turns choosing a number (1-9) corresponding to the board position.
3. The system validates the move and updates the board.
4. The game continues until a player wins or the board is completely filled, resulting in a draw.
5. The result is displayed, and the game ends.

## Game Board Example
```
     |     |     
  1  |  2  |  3  
_____|_____|_____
     |     |     
  4  |  5  |  6  
_____|_____|_____
     |     |     
  7  |  8  |  9  
     |     |     
```
After player moves:
```
     |     |     
  X  |  O  |  X  
_____|_____|_____
     |     |     
  O  |  X  |  O  
_____|_____|_____
     |     |     
  X  |  O  |  X  
     |     |     
```

## Code Structure
- `Main()` method initializes and starts the game loop.
- `Board()` method displays the game board.
- `CheckWin()` method checks for a win or draw condition.
- `NewMethod()` contains the game logic and handles user input.

## Future Enhancements
- Implement a graphical user interface (GUI)
- Add AI for single-player mode
- Improve input validation and error handling

## Author
Developed by Çağrı ÇELEBİOĞLU

## License
This project is open-source and available under the MIT License.

