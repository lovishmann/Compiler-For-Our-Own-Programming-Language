# A Compiler and Virtual Machine for Our Own Programming Language

This project implements a simple compiler and virtual machine (interpreter) for a custom stack-based programming language. The language supports basic arithmetic, conditional jumps, labels, input/output, and control flow.

---

## Features

- Stack-based instruction set (PUSH, POP, ADD, SUB, etc.)
- Conditional jumps (`JUMP.EQ.0`, `JUMP.GT.0`)
- Labels for control flow management
- Input (`READ`) and output (`PRINT`, `PRINT.TOP`)
- Simple programs for number classification and arithmetic

---

## Files

- `interpreter.py` — Python virtual machine that parses and executes programs.
- `program.asm` — Sample program that classifies numbers as zero, negative, or divisible by 3.
- `subtract_example.asm` — Simple program that reads two numbers, subtracts, and prints the result.

---

## How to Run

1. Make sure you have Python 3 installed.

2. Run the interpreter on a program file:

   ```bash
   python interpreter.py program.asm
