# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in-functions for calculation
### Step 2: 
Prepare the lists from the given matrix and assaign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: P PARTHIBAN
#RegisterNumber: 23007965

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(a)
print(rank)
```

## Output:
![image](https://github.com/23007965/RANK-OF-A-MATRIX/assets/138971238/406d657b-005e-463d-8d85-eb4792959779)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

