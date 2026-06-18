# 🔢 Power of 2 Checker (C++)

This C++ program reads an integer from the user and determines whether it is a **power of 2** using bitwise operations.

---

## 🧠 Objective
To practice bitwise operators, conditional statements, and logical reasoning in C++.

---

## 📜 Problem Statement
> Write a C++ program that reads an integer and prints whether it is a power of 2.

---

## 💻 Code Overview
The program:
1. Prompts the user to enter a number (`M`).
2. Uses the condition:
   ```cpp
   if (M > 0 && (M & (M - 1)) == 0)
