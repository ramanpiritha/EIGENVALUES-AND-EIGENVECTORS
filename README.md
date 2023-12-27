# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step1 :
Import the numpy module to use the built-in functions for calculation.
Step 2:
Type the program to be executed.
Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the
given matrix.
Step 4:
Print the value and end the program. 
```
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PIRITHARAMAN R
#RegisterNumber:23013537
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![image](https://github.com/ramanpiritha/EIGENVALUES-AND-EIGENVECTORS/assets/147084116/3ecf87a6-83a6-42c1-95be-f116a10e5194)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
