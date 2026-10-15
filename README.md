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

import numpy as np

matrix = np.array([[2, 2],
                   [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print("Eigenvalues:", eigenvalues)
print("Eigenvectors:\n", eigenvectors)

## Output:

Eigenvalues: [1. 4.]
Eigenvectors:
 [[-0.89442719 -0.70710678]
 [ 0.4472136  -0.70710678]]
 
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
