# Chess-AI-Bot

A simple Chess game with AI opponent built in Python. The AI uses the Negamax optimization algorithm with Alpha-Beta pruning to make moves, and the game is rendered using Pygame.

## Features

- **2-player mode**: Play human vs. human on the same machine.
- **AI opponent**: Challenge the computer powered by a search-based AI.
- **Alpha-Beta Pruning**: Optimized Minimax search to improve performance.
- **Configurable Depth**: Adjust the AI search depth for difficulty.
- **Graphical Interface**: Rendered with Pygame, including chess piece sprites.

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mdeshp11/Chess-AI-Bot.git
   cd Chess-AI-Bot

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt

3. **Run the game**

    ```bash
    python ChessMain.py


## Usage

- **Starting a game**: After launching, the chess board will appear.
- **Moving pieces**: Click on a piece and then click on a destination square.
- **Turn indicator**: Displayed at the top of the window.
- **Restart**: Close and re-run the program to start a new game.

## Configuration
- **AI depth**: In ChessEngine.py, adjust the SEARCH_DEPTH constant to increase or decrease AI difficulty.
- **Window size**: Modify WINDOW_WIDTH and WINDOW_HEIGHT in ChessMain.py.
