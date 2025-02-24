# Flappy-Bird-Game



This repository contains an implementation of the classic **Flappy Bird** game using the **Nand2Tetris** hardware platform. The project demonstrates the design and integration of low-level hardware components, HDL coding, and the software logic required to build a functional game.

## Features
- **Hardware-Level Game**: Implements Flappy Bird mechanics using the Nand2Tetris platform's HDL and CPU simulator.
- **Custom Graphics**: Basic graphics are rendered on the Nand2Tetris display screen.
- **Game Physics**: Simulates gravity, jumps, and collision detection using HDL and assembly code.
- **Pipe Obstacles**: Pipes with random gaps are dynamically generated for the bird to navigate.
- **Score Tracking**: Keeps track of the player's score as the bird successfully passes through pipes.

## Prerequisites
- **Nand2Tetris** software installed: [Download Nand2Tetris](https://www.nand2tetris.org/software)
- Basic understanding of HDL (Hardware Description Language) and the Hack assembly language.

## How It Works
1. **Game Components**:
   - **Bird**: A moving pixel block that responds to user input (jump).
   - **Pipes**: Vertical obstacles with randomly positioned gaps.
   - **Collision Detection**: Checks for overlaps between the bird and pipes or screen boundaries.
2. **Gravity and Physics**:
   - The bird continuously falls due to gravity.
   - Pressing a key generates a jump by changing the bird's vertical velocity.
3. **Scoring System**:
   - Score increases each time the bird successfully passes through a pipe gap.
4. **Game Over**:
   - The game ends when the bird collides with a pipe or the screen edges.
