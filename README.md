# Cramer's Rule in MARIE Assembly

## About the Project

This project implements **Cramer's Rule** using **MARIE Assembly Language** to solve a system of **three simultaneous linear equations with three unknowns**.

The program was developed and tested using the **MARIE Simulator**.

It demonstrates how a mathematical algorithm involving determinants can be implemented using low-level assembly instructions.

## What is Cramer's Rule?

Cramer's Rule is a method used to solve systems of linear equations using determinants.

This program solves equations in the following form:

```text
ax + by + cz = d
ex + fy + gz = h
ix + jy + kz = l
```

The program calculates the main determinant **D** and the determinants **Dx**, **Dy**, and **Dz**.

The three unknowns are then calculated using:

```text
x = Dx / D
y = Dy / D
z = Dz / D
```

A unique solution exists when:

```text
D ≠ 0
```

## Features

- Written in **MARIE Assembly Language**
- Runs using the **MARIE Simulator**
- Solves three simultaneous linear equations
- Calculates three unknowns: **x, y, and z**
- Implements Cramer's Rule using determinants
- Performs arithmetic calculations using low-level assembly instructions
- Demonstrates the implementation of a mathematical algorithm in Assembly Language

## Technologies Used

- MARIE Assembly Language
- MARIE Simulator

## Screenshot

Below is the program running in the MARIE Simulator:

![Cramer's Rule running in MARIE Simulator](https://github.com/Ankush7323/cramers-rule-assembly/blob/main/Running%20Marie%20Sim.jpeg?raw=true)

## How to Run

1. Open the **MARIE Simulator**.
2. Load the program file.
3. Assemble the program.
4. Run the program.
5. Enter the required values for the three equations.
6. The program calculates the determinants.
7. The values of **x**, **y**, and **z** are calculated and displayed.

## Purpose

This project was developed as part of my Computer Science studies to practise **Assembly Language programming** and gain a better understanding of how mathematical algorithms such as Cramer's Rule can be implemented at a low level.

## Author

Suryanshu Bisram
