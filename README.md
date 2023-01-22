# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy dictionary to the python program
### Step 2: Enter the given list of array inside a variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the Eigen values and the Eigen vectors and the output is displayed

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Bharath K
#RegisterNumber:22009080
import numpy as np
a=np.array([[2,2],[1,3]])
value,vector=np.linalg.eig(a)
print(f'Eigen values are {value} and Eigen Vectors are {vector}')
```
## Output:
![output](/eigen%20values.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
