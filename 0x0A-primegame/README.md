# 0x0A. Prime Game

## Description
This repository contains the implementation of the "Prime Game," where two players, Maria and Ben, take turns choosing prime numbers from a set of consecutive integers and removing that number and its multiples from the set. The player who cannot make a move loses the game. The challenge is to determine the winner of each game based on the strategic removal of prime numbers and their multiples.

## Usage
The Prime Game can be run from the command line. Users can input the number of rounds and a list of integers for each round, and the program will simulate the game and announce the winner.

## Requirements
- Python 3.x
- Ubuntu 20.04 LTS

## Game Rules
1. Two players, Maria and Ben, take turns to play.
2. Maria always goes first.
3. On each turn, a player picks a prime number from the set.
4. All multiples of the chosen prime number are removed from the set.
5. The player who cannot make a move loses the game.
6. Both players play optimally.

## Task
### 0. Prime Game
Maria and Ben are playing a game. Given a set of consecutive integers starting from 1 up to and including `n`, they take turns choosing a prime number from the set and removing that number and its multiples from the set. The player that cannot make a move loses the game.

- **Prototype**: `def isWinner(x, nums)`
  - `x` is the number of rounds.
  - `nums` is an array of `n`.
  - Returns: the name of the player that won the most rounds or `None` if the winner cannot be determined.
  - Assumptions: `n` and `x` will not be larger than 10000.
  - No imports are allowed.

#### Example:
```python
x = 3
nums = [4, 5, 1]
print(isWinner(x, nums))  # Output: "Ben"

