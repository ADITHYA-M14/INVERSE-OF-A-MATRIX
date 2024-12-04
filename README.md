# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : The matrix a is a 3×3 square matrix, and its determinant is non-zero, making it invertible.
### Step 2: The np.linalg.inv() function computes the inverse of a.
### Step 3: When a is multiplied by its inverse b, the result will be the identity matrix.
### Step 4: End of the program

## Program:
```
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
```
## Output:
![Screenshot 2024-12-04 153754](https://github.com/user-attachments/assets/4f6773e7-1ba2-4b9b-a8b2-ea013d46c1dc)

## Result:
Thus the inverse of given matrix is successfully solved using python program

