# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(), we can find the solutions.
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ARUN S
RegisterNumber: 24900219
/*

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ARUN S
RegisterNumber: 24900219
/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```
## Output:
![Screenshot 2024-12-22 153153](https://github.com/user-attachments/assets/eb24ae66-6de8-45c9-bd67-c73de8360cfe)
![Screenshot 2024-12-22 153229](https://github.com/user-attachments/assets/3c6cc1b8-cbc8-429b-b039-1a27f00422e2)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

