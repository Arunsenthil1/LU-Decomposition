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
Program to find the L and U matrix.
Developed by: ARUN S
RegisterNumber: 24900219
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu (A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ARUN S
RegisterNumber: 24900219
*/
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![Screenshot 2024-11-28 201708](https://github.com/user-attachments/assets/6bc6f7f7-299e-45ea-97fc-5d87e3e7af51)
![Screenshot 2024-11-28 201722](https://github.com/user-attachments/assets/c44e3357-7d8b-4af0-b618-64e2ded11fb9)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

