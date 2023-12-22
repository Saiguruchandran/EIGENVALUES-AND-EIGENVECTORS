# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: G SAI GURUCHANDRAN
#RegisterNumber:23014037
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
![EXP 4](https://github.com/Saiguruchandran/EIGENVALUES-AND-EIGENVECTORS/assets/144870946/3c3bf55e-211e-4f45-a42c-90e0acaa6709)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
