# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: karsavarthan r r
#RegisterNumber:23003628 
import numpy as np
matrix = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eightvectors=np.linalg.eig(matrix)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eightvectors)
```

## Output:
![output](/Screenshot%202023-11-29%20133650.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
