# Alien Invasion

A complete 2D space shooter game built with **Pygame**, based on the project from *Python Crash Course* (3rd Edition) by Eric Matthes (Chapters 12–14).

## Features

- Player-controlled spaceship that moves left/right and fires bullets
- Waves of aliens that move side-to-side and drop down
- Collision detection between bullets and aliens
- Scoring system with high score tracking
- Increasing difficulty (faster aliens and more of them as levels progress)
- Game over and restart functionality
- Play button on the start screen

## Requirements

- Python 3.8 or higher
- Pygame

Install Pygame with:

```bash
pip install pygame

How to Run

Clone or download this repository.
Open a terminal in the project folder.
Run the game:

Bash python alien_invasion.py

##Controls

Key, Action
← / →, Move ship left/right
Space,Fire bullet
Q, Quit the game
Mouse Click, Start / Restart game

##Project Structure

alien_invasion/
├── alien_invasion.py   # Main game file
├── settings.py         # All game settings
├── ship.py             # Ship class
├── bullet.py           # Bullet class
├── alien.py            # Alien class
├── game_stats.py       # Game statistics
├── scoreboard.py       # Score display
├── button.py           # Play button
└── images/             # Game images (ship.bmp, alien.bmp)


Notes
The images used are simple placeholders. You can replace images/ship.bmp and images/alien.bmp with your own images if you want.
The game automatically creates a high score that persists during the current session.
Press Q at any time to quit cleanly.


Credits
Based on the Alien Invasion project from:
Python Crash Course, 3rd Edition

by Eric Matthes

Published by No Starch Press

Enjoy the game!
