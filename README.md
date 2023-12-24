# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculations.
### Step 2:
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: shruthi D.N
#RegisterNumber:23010231
import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![Screenshot 2023-12-24 155202](https://github.com/Shruthidn27/EIGENVALUES-AND-EIGENVECTORS/assets/138849783/7e427ff6-6077-457c-a8a6-156ef3f0b9da)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
