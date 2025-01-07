# Tetris Game Using Raylib
A classic Tetris game built with C++ and the raylib library. This game uses raylib functions for graphics, input handling, and audio, providing a smooth gaming experience across Windows, macOS, and Linux platforms.

# Features
- Smooth Graphics & Input Handling: Utilizing raylib functions to manage game graphics and inputs.
- Sound Effects: Enjoy immersive sound effects as you play.
- Cross-Platform: Play the game on Windows, macOS, and Linux.
- Scoring System: Earn points for clearing lines and making moves:
  - 100 points for clearing a single line
  - 300 points for clearing two lines
  - 500 points for clearing three lines
  - 1 point for each move down
# How to Play
- Move the Tetrominoes:

   - Use the arrow keys to move the falling pieces (left, right, or down).
   - Press Down Arrow to move the piece faster and Up Arrow to rotate the piece.
- Clear Lines:

   - When a horizontal line is completely filled, it will clear, and you’ll earn points based on the number of lines cleared.
- Objective:

   - The goal is to prevent the screen from filling up while you continue to clear lines.
   - The game ends when the pieces stack up and reach the top of the screen.
- Scoring:

   - Clear lines to earn points and try to score as much as possible.
   - Every line cleared adds to your score:
   - Single line: 100 points
   - Double line: 300 points
   - Triple line: 500 points
   - Each time you move a piece down, you earn 1 point.
# Installation
To run the game on your local machine:

# Prerequisites
Make sure you have C++ and raylib installed. Follow these instructions:

- Install raylib:

   - For Windows: raylib installation on Windows
   - For macOS: raylib installation on macOS
   - For Linux: Use the package manager (e.g., sudo apt install libraylib-dev on Ubuntu).
- Clone this repository:

   - git clone https://github.com/yourusername/tetris-raylib.git
- Navigate to the project folder:

   - cd tetris-raylib
- Build and Run:

   - Use CMake or your preferred C++ build system to compile the project.
   - Once compiled, run the executable to play the game.
