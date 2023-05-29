# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.ANUSHARON
RegisterNumber:212222240010
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.ANUSHARON
RegisterNumber: 212222240010
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A = eval(input())
b = eval(input())
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print (x)
*/
```

## Output:
![lu decomposition]()

![Screenshot (78)](https://github.com/Anusharonselva/LU-Decomposition/assets/119405600/c5383cc5-57ae-4f07-9873-f1f37b06f530)

![Screenshot (79)](https://github.com/Anusharonselva/LU-Decomposition/assets/119405600/cfee562f-cff3-401a-a311-807f7d9d374b)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

