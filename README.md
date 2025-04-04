# GameKille

This game was collaboratively developed by Emanuel Paraschiv and Kacper Lisik as part of our university coursework.

GameKille is a retro-style game console project built using a PIC32 microcontroller. It features classic games such as Snake, Flappy Bird, and Space Invaders, all implemented with low-level C and assembly for an educational, embedded-systems environment.

## Features

- 🐍 **Snake** – Classic snake game with collision detection and score tracking.
- 👾 **Space Invaders** – Retro shooting game with moving enemies and player fire control.
- - 🐦 **Flappy Bird** – Side-scrolling obstacle game with button-controlled jumping.
- 🖥️ **Custom I/O Display** – Game graphics rendered on a custom hardware display.
- 🧠 **Interrupt Handling** – Includes MIPS assembly for handling hardware-level interrupts.


The game is supposed to be played on a pic32 with basic I/O shield game console:

### Compilation and Installation:

toolchain: https://github.com/is1200-example-projects/mcb32tools

1. make
2. make install TTYDEV=/dev/ttyS2
(ttyS# # -> might be different than 2)

### Main Menu Controls:
BTN4: Select
BTN3: Go Down
BTN2: Go Up

### Game Controls (Snake / Space Invaders):
BTN4: Go Up / Shoot
BTN3: Go Down / Special Ability (Not always active, you have to have sufficient combo)
BTN2: Go Left
BTN1: Go Right
