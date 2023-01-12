# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  To find inverse of a matrix using python programming

### Step 2: Import numpy as np.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:  Print result


## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: VAISHALI BALAMURUGAN
#RegisterNumber:22008813
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))


## Output:

https://user-images.githubusercontent.com/121373170/211165038-91fc9b9a-c50b-4358-869f-0e5404650330.png

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
