# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation 
### Step 2:Prepare the lists from each inverse of the matrix and assign in np.array()
### Step 3:Using the np.linalg.solve(), we can find the solutions. 
### Step 4:End the program 

## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by:N.Neethiventhan 
#RegisterNumber23006643
import numpy as np 
matrix = np.array([[2,1,1],[1,1,1],[1,-1,2]])
matrix_inverse = np.linalg.inv(matrix)
print(matrix_inverse)
~~~
## Output:
![image](https://github.com/Neethiventhan123/INVERSE-OF-A-MATRIX/assets/148514848/8995b0dd-653e-49bc-ab54-2456b5a7d9e4)

## Result:
Thus the inverse of given matrix is successfully solved using python program

