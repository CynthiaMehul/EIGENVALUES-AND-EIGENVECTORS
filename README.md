# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Assign matrix to any variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the derived answer

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Cynthia Mehul J
#RegisterNumber: 23009725
import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
values,Vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",Vectors)
```
## Output:
![label](/Output%20Eigen%20values%20and%20vectors.jpg)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
