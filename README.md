# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy,scipy.linalg python library as n,lu
2. Get input from user as x
3. convert x into array
4. lu() returns three values assign it as p,l,u
5. Then print l matrix and u matrix


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S Santhosh
RegisterNumber: 22009296
*/
```
```
'''Program to find L and U matrix using LU decomposition.
Developed by: S Santhosh
RegisterNumber: 22009296
'''
import numpy as np   #from numpy import array
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S Santhosh
RegisterNumber: 22009296
*/
```
```
'''Program to solve a matrix using LU decomposition.
Developed by: S Santhosh
RegisterNumber: 22009296
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```
## Output:
!['output'](/lu1.png)
!['output'](/lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

