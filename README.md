# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X'
include the package in that variable.
4. print the variable 'X' 

## Program:
```
Developed by: G. Pradeep kumar 
RegisterNumber: 212223230150
```
```
(i) To find the L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
```
(ii) To find the LU Decomposition of a matrix
import numpy as np
A=np.array(eval(input()))
B=np.array(eval(input()))
c=np.linalg.solve(A,B)
print(c)
```
## Output:
(i) To find the L and U matrix

![Screenshot 2024-04-24 094630](https://github.com/pradeep23014186/LU-Decomposition/assets/152294642/3592305c-5c1b-4422-b643-ff509b0fd253)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-04-24 094651](https://github.com/pradeep23014186/LU-Decomposition/assets/152294642/bced9551-0e8c-4687-97e1-400b944291fb)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
