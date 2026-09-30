# Cramer's Rule in MARIE Assembly

## About the Project

This project implements **Cramer's Rule** using **MARIE Assembly Language** and was developed and tested using the **MARIE Simulator**.

The program demonstrates how a mathematical algorithm can be implemented using low-level assembly instructions.

## What is Cramer's Rule?

Cramer's Rule is a method used to solve a system of linear equations using determinants.

For two equations:

```text
ax + by = e
cx + dy = f
```

The determinants are calculated as:

```text
D  = ad - bc
Dx = ed - bf
Dy = af - ec

x = Dx / D
y = Dy / D
```

A unique solution exists when `D ≠ 0`.

## Features

- Written in MARIE Assembly Language
- Runs using the MARIE Simulator
- Implements Cramer's Rule
- Performs determinant calculations
- Uses basic assembly instructions for arithmetic and data manipulation
- Demonstrates low-level implementation of a mathematical algorithm

## Technologies Used

- MARIE Assembly Language
- MARIE Simulator

## How to Run

1. Open the **MARIE Simulator**.
2. Load the program file.
3. Assemble the program.
4. Run the program.
5. Enter the required values when prompted.
6. View the calculated results in the simulator.

## Purpose

This project was developed as part of my Computer Science studies to practise Assembly Language programming and gain a better understanding of how mathematical algorithms can be implemented at a low level.

## Author
