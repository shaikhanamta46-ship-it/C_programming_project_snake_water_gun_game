# Snake Water Gun Game (C)

A simple command-line implementation of the classic Snake–Water–Gun game written in C. The computer randomly selects its move, and the player enters their choice to determine the winner according to the game rules.

## Rules

* Snake drinks Water → Snake wins.
* Water douses Gun → Water wins.
* Gun kills Snake → Gun wins.
* Same choices result in a draw.

## Features

* Random computer moves using the `rand()` function.
* Clear win, lose, and draw messages.
* Lightweight and beginner-friendly C project.

## How to Run

1. Compile the program:

   ```bash
   gcc snake_water_gun.c -o game
   ```
2. Execute the program:

   ```bash
   ./game
   ```

Enter `0` for Snake, `1` for Water, or `2` for Gun when prompted and enjoy the game!
