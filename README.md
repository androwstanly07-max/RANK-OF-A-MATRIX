# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
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
<img width="1000" height="388" alt="Screenshot 2026-10-13 221815" src="https://github.com/user-attachments/assets/da29e59a-300d-4dec-a6c7-4f729db74f9a" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

