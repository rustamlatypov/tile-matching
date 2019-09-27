# Classic Tetris and Pentis

Project for the Aalto University course ELEC-A7151 - Object oriented programming with C++.

Developed during November - December, 2018.

## Description

This tile-matching project is a classic Tetris with a Pentis game expansion. Tetris is a well known tile-matching puzzle video game where the players objective is to guide 4-tile-size blocks falling from the upper edge of the screen and try to keep the stack as low as possible. Pentis introduces 1-, 2-, 3-, and 5-tile-size blocks into the game and its difficulty increases differently than in Tetris.

The blocks are controlled by arrow-keys and can be dropped instantly by pressing ```Space```. The controls are in accordance with the Super Rotation System. When a row is complete with tiles, it disappears. The game ends when the stack reaches the point where the new spawning block overlaps with the stack.

Both game modes reward the player basic points for successfully landing a block, one point for each tile the block contains. Elimination points are awarded based on the size of the elimination — the more rows eliminated simultaneously, the better. Drop points are also awarded for every instant drop, according to the height the block is dropped from.

The game keeps track of the top-10 scores and the names of those players. This information is stored locally in a text file. If the player reaches the top-10, the player has the option to submit his/hers name and score and view highscore standings. If the player doesn't reach the top-10, the current highscores are shown. Separate highscores are kept for the game modes.

The difficulty of both game modes increase specifically as a function of the number of eliminations and not of the number of eliminated rows. Tetris spawns the same distribution of blocks but the falling speed increases. The falling speed in Pentis stays constant but the 5-tile-size blocks starts to spawn more frequently. Tetris is faster that Pentis, but only has 7 different blocks. Pentis has 29 different blocks overall and is considered to be a more challenging game mode.


## Building and running

Designed for linux. Following programs and libraries are required to compile the project:
```
• make (4.1-9.1ubuntu1)
• g++ (4:7.3.0-3ubuntu2)
• libsfml-dev (2.4.2+dfsg-4)
```
1. Run ` make `.
2. Run `./main`.
3. Clean up directory by running `make clean`.

## Authors

- Software architecture and UI design: [Rustam Latypov](mailto:rlatypov1337@gmail.fi)
- OS compatibility and UI design: Visa Lintunen
- Game mechanics and [SRS](https://tetris.wiki/SRS) integrity: Kalle Alaluusua
- Game mechanics and UX design: Juho Heimonen

