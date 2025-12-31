

# Snakes and Ladders - FPGA Implementation

This project implements the classic **Snakes and Ladders** game on a **Xilinx Spartan-6 LX9 FPGA** using **VHDL** for the logic. The game utilizes the **LogiCORE Mega Wing module** for joystick control and LCD display output. The design is developed and synthesized using the **Xilinx ISE** tool.

## Features
- **FPGA Implementation**: The game is designed to run on a Xilinx Spartan-6 LX9 FPGA.
- **Joystick Control**: Players control the snake's movement using a joystick.
- **LCD Output**: The game's state (player's position, snake's movement, etc.) is displayed on an LCD screen.
- **VHDL Code**: The game logic is implemented in VHDL for the FPGA.

## Requirements
- **Xilinx Spartan-6 LX9 FPGA** or compatible FPGA board.
- **Xilinx ISE** (Integrated Software Environment) for project synthesis.
- **LogiCORE Mega Wing module** for joystick interfacing.
- **LCD Display** for visual output.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Snakes-and-Ladder.git
   cd Snakes-and-Ladder


2. Open the project in **Xilinx ISE**.
3. Load the appropriate **constraints file** (`.ucf`) and ensure your FPGA is properly set up.
4. Compile the project and upload it to your FPGA board.

## Game Logic

* The player controls the snake's movement using a joystick.
* The LCD screen displays the current game state, including the player's position on the board and the snake's movement.
* The game follows standard Snakes and Ladders rules with randomly determined dice rolls.

## Files

* `CAD971Test.ucf`: User constraints file for FPGA pin assignments.
* `MovementController.vhd`: VHDL code for the movement logic of the game.
* `SevenSegmentController.vhd`: VHDL code to control seven-segment displays (if used).
* `SnakeLadderController.vhd`: VHDL code managing the Snakes and Ladders game mechanics.
* `README.md`: This documentation file.
* `Screenshot_2024-07-09_071636.png`: A screenshot of the project in Xilinx ISE.


## Acknowledgments

* **Xilinx Spartan-6 LX9** FPGA development board for hardware implementation.
* **Xilinx ISE** for the FPGA synthesis and implementation.
* **LogiCORE Mega Wing module** for joystick interface and display handling.


## 📜 License


This project is licensed under the Creative Commons Attribution-NoDerivatives 4.0 International License. You are free to share the work, but you cannot modify it or create derivatives. Proper attribution must be given to the original author.
You can view the full license text here: [CC BY-ND 4.0 License](https://creativecommons.org/licenses/by-nd/4.0/legalcode)
![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY%20ND%204.0-lightgrey)








