# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu,lu_factor,lu_piv
3. Get input from the user as eval(input())
4. Use lu_factor and lu_solve to find LU decomposition
5. print L,U
6. print x

## Program:
```
(i) '''Program to find L and U matrix using LU decomposition.
Developed by: PRAVINRAJJ GK
RegisterNumber: 212222240080 
'''
/*
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
(ii) '''Program to find L and U matrix using LU decomposition.
Developed by: PRAVINRAJJ GK
RegisterNumber: 212222240080 
'''
/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv=lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)
*/
```
## Output:
![image](https://user-images.githubusercontent.com/117917674/232713854-d87f3bcd-38da-4191-8954-a13905a3002f.png)
![image](https://user-images.githubusercontent.com/117917674/232713963-4e19ce98-7df4-4e88-886e-c0c4011abaab.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

