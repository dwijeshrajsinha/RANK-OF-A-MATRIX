# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

# Define the matrix
matrix = np.array([[1, 2, 3],
                   [3, 6, 9]])

# Find the rank
rank = np.linalg.matrix_rank(matrix)

# Display result
print(rank)
```
## Output:
<img width="859" height="573" alt="image" src="https://github.com/user-attachments/assets/d1abb0ce-0b4d-45a7-a0f5-89a4f168e08c" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

