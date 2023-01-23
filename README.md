# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 
import numpy 

### Step 2: 
Assign values for the array

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Print the eigen values and vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: S.Prema latha
#RegisterNumber:22009393
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```

## Output:
![](eigen%20values.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
