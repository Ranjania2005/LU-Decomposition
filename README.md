# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: A.RANJANI
RegisterNumber: 212223230170
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: A.RANJANI
RegisterNumber: 212223230170
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
c=lu_solve((l,p),b)
print(c)
```

## Output:
![Screenshot (190)](https://github.com/Ranjania2005/LU-Decomposition/assets/151624950/05adf7a5-34a5-4c85-b067-8f11e89ad9d0)


![Screenshot (191)](https://github.com/Ranjania2005/LU-Decomposition/assets/151624950/5eea3ad1-59cc-491a-8c7d-d74af5b089ae)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

