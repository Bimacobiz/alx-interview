# 0x08-making_change

## Description

This project focuses on solving the coin change problem, a classic problem from the domain of dynamic programming and greedy algorithms. The objective is to find the minimum number of coins required to make up a given total amount, given a list of coin denominations. The project challenges you to devise a solution that is both correct and efficient by applying your understanding of algorithms and problem-solving strategies.

## Concepts Needed

### Greedy Algorithms

- Understanding how greedy algorithms work and their suitability for the coin change problem.
- Recognizing the limitations of greedy algorithms and scenarios where they might not provide the optimal solution.

### Dynamic Programming

- Understanding the basic principles of dynamic programming as a method to solve optimization problems.
- Understanding the concept of overlapping subproblems and optimal substructure in the context of the coin change problem.

### Algorithmic Complexity

- Analyzing the time and space complexity of algorithms.
- Striving for solutions with lower complexity to meet runtime constraints.

### Problem-Solving Strategies

- Breaking down the problem into smaller, manageable sub-problems.
- Choosing between iterative and recursive approaches to dynamic programming.

### Python Programming

- Manipulating lists and using list comprehensions.
- Implementing functions with efficient looping and conditional statements.

## Resources

### Python Official Documentation

- [More Control Flow Tools](https://docs.python.org/3/tutorial/controlflow.html) (for loops, if statements)

### GeeksforGeeks Articles

- [Coin Change | DP-7](https://www.geeksforgeeks.org/coin-change-dp-7/)
- [Greedy Algorithm to find Minimum number of Coins](https://www.geeksforgeeks.org/greedy-algorithm-to-find-minimum-number-of-coins/)

### YouTube Tutorials

- [Dynamic Programming - Coin Change Problem](https://www.youtube.com/watch?v=NJuKJ8sasGk) for a visual and step-by-step explanation of the dynamic programming approach.

By thoroughly understanding these concepts and utilizing the provided resources, you will be well-prepared to tackle the coin change problem. You will need to decide whether a greedy algorithm suffices for your particular set of coin denominations or if a more comprehensive dynamic programming approach is necessary to ensure correctness and efficiency. This project not only tests algorithmic skills but also reinforces the importance of choosing the right strategy based on problem constraints.

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All files interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file at the root of the project folder is mandatory
- Code should use the PEP 8 style (version 1.7.x)
- All files must be executable

## Tasks

### 0. Change comes from within

Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount total.

- Prototype: `def makeChange(coins, total)`
- Return: fewest number of coins needed to meet total
- If total is 0 or less, return 0
- If total cannot be met by any number of coins you have, return -1
- `coins` is a list of the values of the coins in your possession
- The value of a coin will always be an integer greater than 0
- You can assume you have an infinite number of each denomination of coin in the list

## Example

```python
makeChange([1, 2, 25], 37)  # Output: 7
makeChange([1256, 54, 48, 16, 102], 1453)  # Output: -1

