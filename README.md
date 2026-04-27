# Snakes and Ladders (Python - Turtle Graphics)
A simple interactive Snakes and Ladders game built using Python’s `turtle` module.
The game supports multiple players and follows standard board rules with snakes and ladders.

## Features
> Supports 2–4 players
> Graphical board using Turtle
> Random dice rolls for movement
> Automatic handling of:
    -Snakes (move down)
    -Ladders(move up)
> Displays player positions on the board
> Turn-based gameplay via terminal input

## Technologies Used
> Python
> Turtle (for graphics)
> Random module

## How to Run
1. Make sure Python is installed
2. Run the file:

```bash
python snake_ladder.py
```

3. Enter:
    - Number of players (2–4)
    - Player names and colors

4. Press **Enter** to roll the dice each turn

## Game Rules
1. Players start at position 0.
2. Roll a dice (1–6) to move forward.
3. Landing on:
        - a snake (red) : moves player down
        - a ladder (green) : moves player up
4. Exact roll required to reach **100**
5. First player to reach 100 wins

## Notes
> The game uses basic coordinate mapping for board positions
> Designed as a learning project for:
  - Python programming
  - Game logic
  - Turtle graphics

## Authors
Developed as a group project in 1st year by a team of 4 members.
