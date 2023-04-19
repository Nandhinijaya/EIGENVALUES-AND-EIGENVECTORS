# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 :
get the input from the user
### Step 2:
type import numpy as np
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
then type the print statement
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: E.Nandhini
#RegisterNumber:212222100030
import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![evev](https://user-images.githubusercontent.com/121998147/232981478-8210b38f-32fa-47c8-a3c0-a9a7bbeb001b.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
