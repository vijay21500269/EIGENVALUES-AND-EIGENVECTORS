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
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: R.Vijay
#RegisterNumber:21500269
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
~~~

## Output:
![output](https://github.com/vijay21500269/EIGENVALUES-AND-EIGENVECTORS/blob/main/eig.png?raw=true)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
