# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy library to use its built-in mathematical functions.

### Step 2: Define the matrix as a nested list and assign it using np.array().

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4: Print the calculated rank and end the program.

## Program:

import os
os.environ["OPENBLAS_NUM_THREADS"]= '1"

import numpy as np

matrix = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])

rank = np.linalg.matrix_rank(matrix)

print(rank)

## Output:

2

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

