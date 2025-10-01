# Snake Game

A classic Snake game implementation in Python using Pygame.

## Features

- Classic snake gameplay
- Score tracking
- Collision detection (walls and self)
- Smooth controls
- Food spawning

## Installation

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## How to Play

1. Run the game:
```bash
python snake_game.py
```

2. Controls:
   - **Arrow Keys**: Control the snake's direction
     - ↑ (Up Arrow): Move up
     - ↓ (Down Arrow): Move down
     - ← (Left Arrow): Move left
     - → (Right Arrow): Move right

3. Game Rules:
   - Guide the snake to eat the red food blocks
   - Each food eaten increases your score by 1
   - The snake grows longer with each food eaten
   - Avoid hitting the walls or the snake's own body
   - The game ends when you collide with a wall or yourself

## Game Settings

You can modify these constants in `snake_game.py` to customize the game:
- `BLOCK_SIZE`: Size of each block (default: 20)
- `SPEED`: Game speed/FPS (default: 15)
- Window size: Default 640x480

## Requirements

- Python 3.6+
- Pygame 2.5.2

Enjoy playing!
