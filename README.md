# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: try:
        A_inv = np.linalg.inv(A) 
### Step 3: print(A_inv)
### Step 4: except np.linalg.LinAlgError:
        print("The matrix is singular and cannot be inverted.")

## Program:
    #Program to find the inverse of a matrix.
    #Developed by:  Harish G
    #RegisterNumber:24006523
    import numpy as np
    A = np.array([[1, 0, 3],
                [-1, 2, -2],
                [2, 3, -1]])
    try:
        A_inv = np.linalg.inv(A)
        
        print(A_inv)
    except np.linalg.LinAlgError:
        print("The matrix is singular and cannot be inverted.")
## Output:
![result](<Screenshot 2024-12-10 082929.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

