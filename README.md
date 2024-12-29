# Maze-Game
# The Maze Game

A fun and challenging maze game developed using OpenGL in C. Navigate through the maze, find the correct path, and beat the clock to win!

## Features

- **Start Screen**: Choose between starting a new game, viewing instructions, or quitting.
- **Dynamic Gameplay**: Move the player point through the maze using arrow keys.
- **Time Challenge**: Solve the maze within the time limit.
- **Visual Feedback**: 
  - Starting point marked with a green dot.
  - Exit point marked with a red dot.
  - Player position marked with a blue dot.
- **Winning and Losing Screens**: Displays feedback based on game performance.

## How to Play

1. **Start the Game**:
   - Press `Enter` to proceed from the welcome screen.
   - Press `1` to start a new game.
   - Follow on-screen instructions for navigation.

2. **Objective**:
   - Navigate the maze from the green dot to the red dot.
   - Use the arrow keys to move:
     - Up: Arrow Up
     - Down: Arrow Down
     - Left: Arrow Left
     - Right: Arrow Right

3. **Time Constraint**:
   - Complete the maze within the given time (60 seconds).

4. **Options**:
   - Press `ESC` to return to the main menu.
   - Press `1` to restart the game.

## Installation and Execution

1. **Requirements**:
   - A C compiler that supports OpenGL (e.g., GCC).
   - OpenGL and GLUT libraries installed on your system.

2. **Build and Run**:
   - Compile the program:
     ```bash
     gcc -o maze_game maze_game.cpp -lGL -lGLU -lglut
     ```
   - Run the compiled program:
     ```bash
     ./maze_game
     ```

3. **Controls**:
   - Use the keyboard as specified in the instructions.

## Code Structure

- **Maze Display**: Maze walls are drawn using polygons defined in the `wall` function.
- **Player Movement**: The player's position is updated based on keyboard input.
- **Game Logic**: 
  - Collision detection to ensure valid movements.
  - Timer to track game progress.

## Contributions

Feel free to fork this repository, submit issues, or make pull requests to improve the game!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---
Enjoy the challenge and have fun solving the maze!
