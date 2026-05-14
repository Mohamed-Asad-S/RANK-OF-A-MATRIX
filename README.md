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

<img width="761" height="65" alt="image" src="https://github.com/user-attachments/assets/ba706048-1505-4af6-9ec6-c88a03cbbc9a" />

```
#Program to find the rank of a matrix.
#Developed by: Mohamed Asad S
#RegisterNumber: 212225040238

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
x=np.linalg.matrix_rank(A)
print(x)

```

## Output:

<img width="307" height="176" alt="image" src="https://github.com/user-attachments/assets/4e170cce-bb80-4c36-a907-f96d343b81e0" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

