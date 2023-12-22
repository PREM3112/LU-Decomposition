# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: PREM.R
RegisterNumber: 23002486
*/
import numpy as np
from scipy.linalg import lu
a= np.array(eval(input()))
p,L,u= lu(a)
print(L)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: PREM.R
RegisterNumber:23002486 
*/
import numpy as np
from scipy.linalg import lu
a= np.array(eval(input()))
p,L,u= lu(a)
B= np.array([4,5,7])
X= np.linalg.solve(a,B.T)
print(X)
```

## Output:
![lu decomposition]()
![lu decomposition](https://github.com/PREM3112/LU-Decomposition/assets/145449383/85e488bc-dd08-458f-83ef-d5a2dae64261)
![lu](https://github.com/PREM3112/LU-Decomposition/assets/145449383/34b7bb7b-1cf9-43c5-93f5-c27c05864a66)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

