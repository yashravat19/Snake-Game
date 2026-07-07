# SnakeGame
# Snake Game in C++

## Description
This is a simple **Snake Game** implemented in **C++** using the console. The game consists of a snake that moves around the board, eating food to grow in size. The game ends if the snake collides with the walls or itself.

## Features
- Playable using **WASD** keys for movement.
- Snake grows when it eats food.
- The score increases with each food eaten.
- The game ends when the snake collides with itself or the walls.
- Uses `conio.h` for input handling (_Windows_) and `windows.h` for timing.

## Controls
| Key  | Action |
|------|--------|
| `W`  | Move Up |
| `S`  | Move Down |
| `A`  | Move Left |
| `D`  | Move Right |
| `X`  | Exit Game |

## Requirements
- A **C++ compiler** (such as MinGW for Windows or g++ for Linux/Mac).
- **Windows OS** (or modify for Linux using `ncurses.h` instead of `conio.h`).
- **Terminal or Command Prompt** for running the program.

## How to Compile and Run
### Windows:
1. Open a terminal (Command Prompt or PowerShell).
2. Compile the program using:
   ```sh
   g++ SnakeGAME.cpp -o SnakeGAME.exe
3.Run the game :
```sh
SnakeGAME.exe
