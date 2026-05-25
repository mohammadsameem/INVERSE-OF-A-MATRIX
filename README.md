# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: 
End the program
## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: Sameem
#RegisterNumber: 212225040242
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
os.environ["MKL_NUM_THREADS"] = "1"
import numpy as np
matrix = np.array([[6, 2, 3],
                  [3, 1, 1],
                  [10, 3, 4]])
inverse = np.linalg.inv(matrix)
print(inverse)
~~~
## Output:
<img width="1505" height="655" alt="image" src="https://github.com/user-attachments/assets/651adc83-0bdf-464a-9f0c-d02d0577aa84" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

