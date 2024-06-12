# gamekille

This game was collaboratively developed by Emanuel Paraschiv and Kacper Lisik as part of our university coursework.

The game is supposed to be played on a pic32 with basic I/O shield game console:

Compilation and Installation:

toolchain: https://github.com/is1200-example-projects/mcb32tools

1. make
2. make install TTYDEV=/dev/ttyS2
(ttyS# # -> might be different than 2)

Main Menu Controls:
BTN4: Select
BTN3: Go Down
BTN2: Go Up

Game Controls (Snake / Space Invaders):
BTN4: Go Up / Shoot
BTN3: Go Down / Special Ability (Not always active, you have to have sufficient combo)
BTN2: Go Left
BTN1: Go Right
