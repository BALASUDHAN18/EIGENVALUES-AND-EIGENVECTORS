# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy folder as np
### Step 2: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 3:
print the values of eigen values and eigen vectors.
### Step 4: 
execute the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Balasudhan P
#RegisterNumber: 212222240017
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues, "and Eigen Vectors are",evector)
```
## Output:
![Annotation 2023-04-15 201811](https://user-images.githubusercontent.com/118807740/232280227-92cd34a5-d06c-408b-a39b-f682b945ad13.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
