# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Commence the program 
### Step 2: 
Enter the matrix by importing numpy
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the result and stop the program

## Program:
~~~
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,Vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are", Vectors)
~~~
## Output:
![output](ev.jpg)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
