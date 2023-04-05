# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Create a variable and and assign the value as array for a matrix.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Use print for execution and to get a Output.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Surendhar A
#RegisterNumber: 212222110049
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![image](https://user-images.githubusercontent.com/118352907/229992323-cac47b74-c7d1-45bc-9c30-46f486ac26c2.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
