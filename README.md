# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:End the program
## Program:
```
import numpy as np
A= np.array([[3,2,5], [1,1,2],[3,3,6]])
X= np.linalg.matrix_rank(A)
print (X)
```
## Output:
<img width="1245" height="755" alt="expt-2" src="https://github.com/user-attachments/assets/40d586f4-8455-484e-8a85-a568d1c8c2f1" />

<img width="1233" height="307" alt="expt-2 output" src="https://github.com/user-attachments/assets/751c9d05-ae6a-461c-ba44-78eafb6a0cdb" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

