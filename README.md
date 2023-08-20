# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step1 :
import numpy as np

Step 2:
put the given values in the np.array command

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
print the program and get the output
```
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: LINGESWARAN K
#RegisterNumber:212222110022
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/Lingeswaran04/EIGENVALUES-AND-EIGENVECTORS/assets/119103865/33ce1bb1-7e25-4bdf-8b70-2e8afe457d58)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
