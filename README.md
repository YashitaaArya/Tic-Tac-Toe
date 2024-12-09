# NxN TIC-TAC-TOE GAME

Welcome to the **NxN Tic-Tac-Toe Game**! This is a console-based implementation of the classic Tic-Tac-Toe game that supports an NxN board, where N can be any size greater than or equal to 3. It is a two-player game that dynamically adjusts to the board size and determines the winner based on consecutive marks.

## Features
- Supports boards of any size (3x3, 4x4, 5x5, etc.).
- User-friendly interface with clear board visualization.
- Players take turns to place their marks (X and O).
- Automatically checks for wins, draws, or invalid moves.
- Scalable and easy to modify.

## How to Play
1. Run the program in your terminal or any C++ compiler.
2. Enter the size of the board (N).
3. Players will take turns to enter the row and column indices to place their mark.
4. The game ends when:
   - A player forms a straight line (row, column, or diagonal) of N consecutive marks.
   - The board is full with no winner (draw).

## Requirements
- C++ compiler.
- Terminal or IDE to run the program.

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YashitaaArya/Tic-Tac-Toe.git
cd Tic-Tac-Toe
```
### 2. Compile the Code
- Use any C++ compiler to compile the code. For example, using g++:
```bash
g++ -o tictactoe tictactoe.cpp
```
### 3. Run the Game
- Execute the compiled file:
```bash
./tictactoe
```

## File Structure
- **tictactoe.cpp** : Contains the main logic for the NxN Tic-Tac-Toe game.
- **output/** : Directory for storing game outputs or logs (optional, customizable)

## Future Enhancements
- Implement a GUI version of game.
- Add AI for single-player mode.
- Include save and load functionality for game states.
- Optimize the win-checking logic for better performance on larger boards.

## Contributions
Contributions are welcome! Do fork this repository, make your changes and submit a pull request. Ensure the code is well-commented and follows consistent styling.

## Contact
If you have any questions or suggestions, feel free to reach out via:
- **GitHub**: [YashitaaArya](https://github.com/YashitaaArya)
- **Email**: yashitaaarya23@gmail.com

Enjoy playing the NxN Tic-Tac-Toe game and happy coding! 🎮✨
