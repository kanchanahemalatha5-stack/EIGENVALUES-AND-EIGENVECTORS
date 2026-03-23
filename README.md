# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Write a python program for the given matrix
### Step 2:
Import numpy library
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Run the code and get the output

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Kanchana M 
#RegisterNumber:25016997
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector=np.linalg.eig(A)
print(f'Eigen values are {values} and Eigen Vectors are {vector}')
```
## Output:
![alt text](<Screenshot 2026-03-23 204622.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
