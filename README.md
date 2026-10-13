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
<img width="1896" height="904" alt="Screenshot 2026-10-13 222605" src="https://github.com/user-attachments/assets/fe34b56a-0917-432e-977e-0bd08288f019" />
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

