# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each linear equations and assign in np.array()

Step 3: Using the np.linalg.solve(), we can find the solutions.

Step 4: End the program 

## Program:
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: PRAVEENKUMAR S
RegisterNumber: 22004035
*/
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by: PRAVEENKUMAR S
RegisterNumber: 22004035
*/
```
import numpy as np 
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
```

## Output:
![lu dcomposition](https://user-images.githubusercontent.com/119559827/214846715-f5a8171b-1bc3-4cd9-af95-3777e44de9bc.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

