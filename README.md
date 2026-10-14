# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module to use the built in function for calculations
### Step 2: Prepare the given matrix and assign it to np.array()
### Step 3: Using the np.linalg.inv(),we can find the solutions.
### Step 4: End the program

## Program:

#Program to find the inverse of a matrix.

#Developed by:Kamalesh.P 

#RegisterNumber:26014307

import os 

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])

b = np.linalg.inv(a)

print(b)

## Output:<img width="1404" height="831" alt="Screenshot 2026-10-14 105225" src="https://github.com/user-attachments/assets/6170d0ab-4c07-4f9c-857b-65d84c70d07d" />
<img width="1319" height="405" alt="Screenshot 2026-10-14 105239" src="https://github.com/user-attachments/assets/d0ec9de3-5ddf-4f13-b9c7-dae06a1c2244" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

