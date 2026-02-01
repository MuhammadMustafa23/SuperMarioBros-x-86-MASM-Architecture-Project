Super Mario Bros - Assembly x86

A complete Mario-style platformer game written entirely in x86 Assembly using the Irvine32 library. Developed as a semester project for BSCSA.

Features

- Full Game Engine: Physics, collision detection, gravity, jumping mechanics
- Multiple Levels: 
  - Level 1-1, 1-2, 1-3 with progressive difficulty
  - Boss level with boss AI and attacks
- Dynamic Scrolling: Screen-to-screen transitions within levels
- Power-ups: 
  - Spring Mushroom (high jump)
  - Star (adds time bonus)
- Enemy Types:
  - Goombas (3 per level)
  - Koopa Troopa (with shell mechanics)
- Boss Battle: Final boss with health, projectile attacks, and phases
- Bonus Room: Secret castle room with timed coin collection
- Sound System: Background music and sound effects using Windows API
- Score System: High score saving to file, time bonuses, coin collection
- Complete UI: Score, coins, lives, timer, boss health display
- Menu System: Main menu, instructions, high score viewer

Controls

- Movement: 
  - A/Left Arrow: Move left
  - D/Right Arrow: Move right
  - W/Up Arrow: Jump
  - Space: Double jump (when in air)
- Game Controls:
  - ESC: Pause game
  - X: Exit/Quit

Gameplay Mechanics

- Collect coins (O) for points
- Defeat enemies by jumping on them
- Avoid side/bottom collisions with enemies
- Reach the flag to complete levels
- Defeat boss by jumping on it 5 times
- Collect power-ups for special abilities
- Enter bonus rooms for extra coins

Technical Details

- Language: x86 Assembly
- Library: Irvine32
- Compilation: MASM (Microsoft Macro Assembler)
- Graphics: Console-based character graphics
- Sound: Windows MessageBeep API
- File I/O: Score saving to text file

Project Structure

- `Source.asm`: Main game file (complete implementation)
- Game divided into modular procedures:
  - Main game loop
  - Physics engine
  - Collision detection
  - Enemy AI
  - UI rendering
  - Sound system
  - File I/O for scores

 Requirements

- MASM assembler
- Irvine32 library
- Windows OS (for sound API)
- Console application support

## How to Run

1. Assemble with MASM:
