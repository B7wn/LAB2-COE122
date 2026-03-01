# Experiment 2: Boolean Function

## Pre-Experiment Question 1.1

### SOP Form
**F = A.B + A’.B’**

---

## Objective
Implement the given Boolean function using digital simulation software and show the circuit design and truth table.

---

## Circuit Idea
To implement the function:

F = A.B + A’.B’

Steps:
1. Use NOT gates to get A' and B'.
2. Use an AND gate for inputs A and B.
3. Use another AND gate for inputs A' and B'.
4. Use an OR gate to combine the outputs of the two AND gates.

This function is equivalent to an **XNOR gate**.

---

## Truth Table

| A | B | A' | B' | A.B | A'.B' | F |
|---|---|----|----|-----|-------|---|
| 0 | 0 | 1  | 1  | 0   | 1     | 1 |
| 0 | 1 | 1  | 0  | 0   | 0     | 0 |
| 1 | 0 | 0  | 1  | 0   | 0     | 0 |
| 1 | 1 | 0  | 0  | 1   | 0     | 1 |

---

## ICs Used
- 7408 (AND Gate)
- 7432 (OR Gate)
- 7404 (NOT Gate)

---

## Software
Digital Logic Simulation Software
