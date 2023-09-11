# battle-bomber

## Introduction

This is a C++ game where two players battle it out in a grid-based arena filled with obstacles and bombs. The goal is to strategically place bombs, destroy obstacles, and defeat your opponent while staying alive. (Co-created with @hsiehwilson)

## Features

- Grid-based game with randomized obstacles.
- Two players with distinct controls.
- Two types of obstacles: indestructible walls and destructible obstacles.
- Bombs with an explosion radius.
- Damage calculation based on proximity to bomb explosions.
- Scoreboard to track points.
- Health board to monitor player health.
- Timer-based game rounds.

## Gameplay

Players must strategically navigate the grid, place bombs, and defeat their opponent while avoiding bomb explosions and obstacles. The game features the following key elements:

### Installation

1. Clone this repository.
2. Compile the C++ source code using your preferred C++ compiler.
3. Run the executable.

### Controls

- Player 1 (Arrow Keys to move, Enter to place bombs)
- Player 2 (WASD to move, Spacebar to place bombs)

### Scoring

- Players earn points for damaging their opponents and destroying obstacles.

### Health

- Each player starts with a certain amount of health.
- Health decreases when a player is close to a bomb explosion, including their own.

### Game Over

The game can end in two ways:

1. A player's health reaches zero, resulting in a victory for the other player.
2. The timer runs out, and the player with the most points wins.

## How to Play

1. Start the game by running the executable.
2. Navigate the grid using the specified controls.
3. Strategically place bombs to damage your opponent and destroy obstacles.
4. Monitor your health and score on the respective boards.
5. Play until a player wins or the timer runs out.

