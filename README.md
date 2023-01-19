# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step1
Import the numpy module to use the built-in functions for calculations.

### Step 2:
Prepare the lists from each equations and assign in np.array().

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:M.AJAY ASWIN 
#RegisterNumber:22009241
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![output](https://user-images.githubusercontent.com/118679692/213350892-076417b6-10ed-455b-bda3-73ec6b02659a.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
