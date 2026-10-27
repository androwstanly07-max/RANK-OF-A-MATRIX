# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step 1: Import the numpy module to use the built-in functions for calculation
### Step 2:Prepare the lists from each linear equations and assign in np.array()
### Step 3:Using the np.linalg.matrix_rank, we can find the solutions.
### Step 4:End the prograM
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
sol=np.linalg.matrix_rank(A)
print(sol)
```
## Output:
<img width="1896" height="904" alt="Screenshot 2026-10-13 222605" src="https://github.com/user-attachments/assets/6727f87d-c7d9-4915-9a8b-ee3ad66d4414" />
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

