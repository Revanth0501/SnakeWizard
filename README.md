## SnakeWizard

**Description:**
This is a simple console-based Snake Game implemented in C++. The game allows players to control a snake using keyboard inputs to navigate through the game board, collect fruits, and avoid collisions with walls and the snake itself. The objective of the game is to maximize the score by eating fruits without colliding with walls or the snake's own body.

**Features:**
- Two game modes:
  1. Killer walls: Colliding with walls results in game over.
  2. Transparent walls: Snake wraps around the screen when hitting the boundary.
- Score tracking: Players earn points by eating fruits.
- Game over conditions: Colliding with walls or the snake's own body ends the game.
- Restart option: Players can choose to play again after a game over.

**Instructions:**
1. Use the following keys to control the snake:
   - 'a': Move left
   - 'd': Move right
   - 'w': Move up
   - 's': Move down
   - 'x': Quit the game
2. In the killer walls mode, avoid colliding with walls to continue the game.
3. In the transparent walls mode, the snake wraps around the screen when reaching the boundary.
4. Eat fruits ($) to increase your score.
5. When the game ends, press 'y' to play again.

**Dependencies:**
- This game requires a C++ compiler that supports the standard libraries used in the code.
- The game utilizes the `<iostream>`, `<conio.h>`, and `<windows.h>` libraries for console input/output and screen manipulation.

**Installation:**
1. Clone the repository to your local machine.
2. Compile the source code using a C++ compiler.
3. Run the executable file generated after compilation.
