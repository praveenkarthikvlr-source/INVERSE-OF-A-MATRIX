# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in function for calculation
### Step 2: prepare the list and assign it to np.array()
### Step 3: using the np.linalg.inv(), we can find the inverse of the given matrix
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:praveen kumar k
#RegisterNumber:212225230216
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a = np.array([[6,2,3],[3,1,1],[10,3,4]])
x = np.linalg.inv(a)
print(x)
```
## Output:
<img width="1297" height="303" alt="image" src="https://github.com/user-attachments/assets/df4ab6bb-0861-4699-ba2a-5d4fd02f18ae" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

