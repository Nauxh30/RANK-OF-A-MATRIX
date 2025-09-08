# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the required NumPy library using import numpy as np.
### Step 2: 
Define the matrix as a NumPy array (example: A = np.array([[1, 2, 3], [3, 6, 9]])).
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Store the result in a variable (e.g., rank) and display the rank of the matrix using the print() function.
## Program:
```python
import numpy as np
A = np.array([[1, 2, 3],[3, 6, 9]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
<img width="397" height="177" alt="Screenshot 2025-09-08 093031" src="https://github.com/user-attachments/assets/a08d0249-d7f2-45d4-b862-72ea837c2a49" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

