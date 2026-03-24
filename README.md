# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm

1.Initialize Inputs: Read the given square matrix A and the constant vector B.

2.Decompose Matrix: Factorize matrix A into a lower triangular matrix (L) and an upper triangular matrix (U) so that A = L * U.

3.orward Substitution: Solve the equation L * Y = B to find the temporary vector Y.

4.Backward Substitution: Using that vector Y, solve the equation U * X = Y to find your final solution vector X. Print the result.

## Program:

'''Program to find the L and U matrix.
Developed by: SARATHI M
RegisterNumber: 212225040386 '''

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


## Output:


<img width="1151" height="340" alt="image" src="https://github.com/user-attachments/assets/e557f067-fbbf-4d70-8240-548a9316687e" />



![PNG 1](https://github.com/user-attachments/assets/4231ba3e-b048-4e4c-ab5d-bf435a2087c6)


<img width="1246" height="243" alt="image" src="https://github.com/user-attachments/assets/d6763b73-cfad-44f8-9f23-22c5c43a93c7" />


![PNG 2](https://github.com/user-attachments/assets/d1715bf1-842c-4134-b8cd-2601026a9171)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

