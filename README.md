# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program.
### Step 2: 
Prepare the lists from given matrix.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Prajin S
#RegisterNumber: 23012918
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are',values,'and Eigen Vectors are',vectors)
```

## Output:
![Eigen](https://github.com/Prajin19/EIGENVALUES-AND-EIGENVECTORS/assets/144979377/a29dd24f-8737-4730-a05f-4fc67540f225)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
