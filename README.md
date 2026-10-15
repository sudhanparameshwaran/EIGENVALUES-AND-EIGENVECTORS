# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use its built-in functions for matrix operations.

### Step 2: Define the matrix for which you want to find the eigenvalues and eigenvectors using np.array().

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: Print the computed eigenvalues and eigenvectors.

## Program:

import os
os.environ["OPENBLAS_NUM_THREADS"]= "1"

import numpy as np

matrix = np.array([[2, 2],
                   [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print("Eigenvalues:", eigenvalues)
print("Eigenvectors:\n", eigenvectors)

## Output:
<img width="1245" height="783" alt="{1FC749A3-BC5F-408C-B089-90132DB37225}" src="https://github.com/user-attachments/assets/34a7f6e0-529a-4845-ba2a-8be21a5d02c7" />

 
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
