# hw-02a: Triangle Classification

## Project Overview

This assignment focuses on developing a Python program to classify triangles based on their side lengths. Additionally, unit tests have been written to verify the correctness of the triangle classification logic.

The project includes:
1. `Triangle.py`: A Python script that contains the function `classify_triangle()` to determine the type of triangle based on the lengths of its three sides.
2. `TestTriangle.py`: A Python script with unit tests for the `classify_triangle()` function to ensure that the function handles various inputs correctly.

## Files

- **`Triangle.py`**: This file contains the core logic to classify triangles into one of the following categories:
  - **Equilateral**: All three sides are equal.
  - **Isosceles**: Two sides are equal.
  - **Scalene**: All sides are different.
  - **Right**: The triangle is a right triangle, which satisfies the Pythagorean theorem.
  
- **`TestTriangle.py`**: This file contains test cases that verify the correctness of the `classify_triangle()` function using different combinations of side lengths. The tests are written using the Python `unittest` framework.
