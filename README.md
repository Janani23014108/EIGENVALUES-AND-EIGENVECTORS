# EIGENVALUES-AND-EIGENVECTORS
Name:J.JANANI

Register no:212223230085

Department:B.Tech AIDS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:

import numpy as np

A=np.array([[4,2],[2,4]])

Eigen_Values,Eigen_Vectors=np.linalg.eig(A)

print("Eigen values are",Eigen_Values,"and Eigen Vectors are",Eigen_Vectors)


## Output:
![MAths exp 4](https://github.com/Janani23014108/EIGENVALUES-AND-EIGENVECTORS/assets/146822085/9825546e-6312-4d28-a9c0-e9beee2e34c8)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
