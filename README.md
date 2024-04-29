# Hack Assembler

This is a simple assembly code assembler implemented in Python. It takes assembly code files (.asm) as input and generates corresponding machine code files (.hack).

P.S: This assembler solution is designed for the Nand2Tetris Project 6.
https://drive.google.com/file/d/1CITliwTJzq19ibBF5EeuNBZ3MJ01dKoI/view

This README provides an overview of the project, including its objective, contract, test programs, and usage instructions. Adjustments can be made as needed to match the specific implementation details.


## Table of Contents

- [Objective](#objective)
- [Contract](#contract-as-described-in-the-project)
- [Test Programs](#test-programs-provided-by-the-project)
- [Usage](#usage)
- [File Structure](#file-structure)

## Objective
The objective is to translate Hack assembly language programs into Hack binary code. This is a fundamental step in understanding how high-level code is deployed on target hardware platforms and how it can be optimized for better performance.

## Contract (as described in the Project)
When supplied with a Prog.asm file containing valid Hack assembly language code, your assembler should correctly translate it into Hack binary code and store it in a file named Prog.hack, located in the same folder as the source file. If a file with the same name already exists, it should be overridden. The output produced by your assembler must be identical to the output produced by the supplied assembler.

## Test Programs (provided by the project)
It provides four test programs to validate the assembler:
- **Add.asm:** Adds the constants 2 and 3, and puts the result in R0.
- **Max.asm:** Computes max(R0, R1) and puts the result in R2.
- **Rect.asm:** Draws a rectangle at the top-left corner of the screen. The rectangle is 16 pixels wide and R0 pixels high.
- **Pong.asm:** A classical single-player arcade game described in detail in Project 4. This large assembly file will stress-test your assembler.

## Usage

To use the assembler, follow these steps:

1. Ensure you have Python installed on your machine.

2. Prepare your assembly code files in the `files` list in `assembler.py`. Add the paths to your assembly code files (e.g., `add/Add`, `max/Max`, etc.).

3. Run the assembler script:

4. The assembler will process each assembly code file specified in the `files` list and generate corresponding machine code files in the same directory.

## File Structure

The project directory contains the following files:

- `Assembler.py`: The main Python script that implements the assembler logic.
- `example.asm`: An example assembly code file for demonstration purposes.
- `example.hack`: The machine code file generated by the assembler from `example.asm`.
- `README.md`: This README file providing information about the project.

