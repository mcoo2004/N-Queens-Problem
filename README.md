# N-Queens-Problem
N-Queens Problem

## Overview

This programming assignment involves solving the N-Queens problem, which is a classic problem in computer science and chess. The goal is to place N queens on an N×N chessboard in such a way that no two queens threaten each other. Accordingly, no two queens can share the same row, column, or diagonal.

## Programming Languages

You can implement the solution in any of the following programming languages:
- C
- C++
- Java
- Python

## Instructions

### Input

- The program prompts the user to enter a number for N (1 to 9), representing the number of queens and the size of the chessboard (N×N).

### Output

- The solution is displayed as a binary matrix where:
  - `1` represents a queen placed on the chessboard.
  - `0` represents an empty space.
- If no solution exists for the given N, the program prints: `Solution does not exist`.
- If more than one solution exists, print only one possible solution and a statement indicating the number of possible solutions.


## Sample Output

### Test 1:
```
N = 2
The solution does not exist for N = 2.
```

### Test 2:
```
N = 4
0 1 0 0
0 0 0 1
1 0 0 0
0 0 1 0
The solution for N = 4 can produce two different solutions.
```

