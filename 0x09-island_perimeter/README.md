# 0x09-island_perimeter

## Overview

This project aims to solve the problem of calculating the perimeter of a single island in a grid represented by a 2D array of integers. The goal is to develop a Python function `island_perimeter(grid)` that returns the perimeter of the island described in the grid.

## Problem Statement

Given a 2D grid representing an island, where each cell is either land (1) or water (0), the task is to calculate the perimeter of the island. The grid is completely surrounded by water, and there is only one island (or nothing). The island doesn’t have any "lakes" (water inside that isn’t connected to the water surrounding the island). Cells are connected horizontally/vertically (not diagonally), and the grid is rectangular, with its width and height not exceeding 100.

## Concepts Needed

- **2D Arrays (Matrices):**
  - Accessing and iterating over elements in a 2D array.
  - Understanding how to navigate through adjacent cells (horizontally and vertically).
- **Conditional Logic:**
  - Applying conditions to determine whether a cell contributes to the perimeter of the island.
- **Counting Techniques:**
  - Developing a method to count the edges that contribute to the island’s perimeter.
- **Problem-Solving Strategies:**
  - Breaking down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.
- **Python Programming:**
  - Nested loops for iterating over grid cells.
  - Conditional statements to check the status of adjacent cells.

## Requirements

### General

- Allowed editors: vi, vim, emacs.
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3.
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/python3`.
- A `README.md` file at the root of the folder of the project is mandatory.
- Code should use the PEP 8 style (version 1.7).
- No importing of any modules allowed.
- All modules and functions must be documented.
- All files must be executable.

## Usage

To use this solution, you can copy the provided code and integrate it into your project. The function `island_perimeter(grid)` takes a 2D grid as input and returns the perimeter of the island.

```python
def island_perimeter(grid):
    # Implementation of island perimeter calculation
    pass

# Example usage
grid = [
    [0, 0, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]
print(island_perimeter(grid)) # Output: 12

