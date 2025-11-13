# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm:

### Step1 : Importing numpy library.
### Step 2: Defining the matrix using np.array()
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigen values and eigen vectors


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Yuvan shankar M
#RegisterNumber: 212224220126
```
```
import numpy as np
matrixA= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigen_values,eigen_vectors= np.linalg.eig(matrixA)
print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vectors}")
```

## Output:

<img width="1301" height="426" alt="image" src="https://github.com/user-attachments/assets/a72a4888-52ae-4f85-84f0-675fd264b4ad" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
