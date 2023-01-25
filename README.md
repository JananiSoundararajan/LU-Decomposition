# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and scipy packages.
2. Read the input matrix as two dimensional array.
3. Call the Built in function lu() to decompose the array.
4. print the output.

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: JANANI.S
RegisterNumber: 22008491
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## Output:
![OUTPUT1](lumat.png)

## Algorithm
1. Import numpy as np.
2. Read the input matrix as two dimensional array.
3. Call the built in function lu_solve() to solve the matrix using LU decomposition.
4. Print the output.

(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: JANANI.S
RegisterNumber: 22008491
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![OUTPUT](ludecomp.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

