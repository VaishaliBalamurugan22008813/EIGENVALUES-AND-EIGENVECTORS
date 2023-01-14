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
#Program to find the eigen values and eigen vector

#Developed by: VAISHALI BALAMURUGAN

#RegisterNumber:22008813

```
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

![eigenoutput](https://user-images.githubusercontent.com/119390134/212458011-270a986d-5e64-4a11-9d17-4cc2fd62b70d.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
