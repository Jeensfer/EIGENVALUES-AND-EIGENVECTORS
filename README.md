# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the required libraries os and numpy.
### Step 2: Set the OpenBLAS thread count to 1 using os.environ["OPENBLAS_NUM_THREADS"]="1".
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Jeensfer Jo
#RegisterNumber: 212225240058
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
<img width="1154" height="759" alt="image" src="https://github.com/user-attachments/assets/009075ff-b734-41d4-bd8a-502cc0b66148" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
