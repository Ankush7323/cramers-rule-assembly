# Cramer's Rule in MIPS Assembly

## About the Project

This project implements **Cramer's Rule** using **MIPS Assembly Language**. It was developed and tested using the **MARS (MIPS Assembler and Runtime Simulator)**.

The program demonstrates how a mathematical algorithm can be implemented using low-level assembly instructions.

## What is Cramer's Rule?

Cramer's Rule is a method used to solve a system of linear equations using determinants.

For two equations:

```text
ax + by = e
cx + dy = f
```

The solution can be calculated using:

```text
D  = ad - bc
Dx = ed - bf
Dy = af - ec

x = Dx / D
y = Dy / D
```

The system has a unique solution when `D ≠ 0`.

## Features

- Written in MIPS Assembly Language
- Runs using the MARS simulator
- Accepts values for a system of linear equations
- Calculates the required determinants
- Uses Cramer's Rule to calculate the values of `x` and `y`
- Demonstrates arithmetic operations and user input/output in MIPS Assembly

## Technologies Used

- MIPS Assembly Language
- MARS (MIPS Assembler and Runtime Simulator)

## How to Run

1. Download and open the MARS simulator.
2. Open the `.asm` file from this repository.
3. Click **Assemble**.
4. Click **Run**.
5. Enter the requested values in the console.
6. The program will calculate and display the result.

## Purpose

This project was created as part of my Computer Science studies to practise Assembly Language programming and understand how mathematical algorithms can be implemented at a lower level.

## Author

Suryanshu Bisram
