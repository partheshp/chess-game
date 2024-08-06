# Chess Game

## About

This project is a simple chess game implemented in C++. It provides the basic functionality to set up a chessboard, make moves, and check for game conditions such as check and checkmate.

## Features

* **Basic Chess Mechanics:** Implements fundamental chess rules including piece movements, captures, and checks.
* **Game Setup:** Initializes a standard 8x8 chessboard with all pieces in their starting positions.
* **Move Validation:** Ensures moves are legal according to chess rules.

## Getting Started: 

### Pre-requesites:

* A C++ compiler
* CMake

### Installation:

1. Clone the repository:
```bash
git clone https://github.com/partheshp/chess-game.git
cd chess-game
```

2. Build the project:
```bash
mkdir build
cd build
cmake ..
make
```

3. Run the game:
```bash
./chess-game
```

## File Stucture:

* `CMakeLists.txt`: Build configuration file.
* `main.cpp`: Main entry point for the game.
* `Game/`: Directory containing game logic and helper functions.
* `Assets/`: Contains any assets or additional resources.

