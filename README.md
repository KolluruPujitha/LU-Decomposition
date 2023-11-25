# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kolluru Pujitha
RegisterNumber: 23002983
*/
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
Developed by: Kolluru Pujitha
RegisterNumber: 23002983
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
P=lu_solve((lu,piv),B)
print(P)

## Output:
![Alt text](<Screenshot 2023-11-25 120153.png>)
![Alt text](<Screenshot 2023-11-25 120210.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

