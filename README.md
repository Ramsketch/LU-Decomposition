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
/*Program to find L and U matrix using LU decomposition.
Developed by: RamKumar S
RegisterNumber: 212225240115*/

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
Program to solve a matrix using LU decomposition.
Developed by: RamKumar S
RegisterNumber: 212225240115*/

# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input())) 
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)


```

## Output:
(i) To find the L and U matrix

<img width="1886" height="922" alt="image" src="https://github.com/user-attachments/assets/b68bea51-fa76-4f29-b555-be776aa9ecc1" />
<img width="1882" height="917" alt="image" src="https://github.com/user-attachments/assets/2ee0bed8-b901-40c2-8373-8d42aa8bbd93" />

(ii) To find the LU Decomposition of a matrix

<img width="1864" height="922" alt="image" src="https://github.com/user-attachments/assets/28edd536-c308-417d-a232-41905b552eb9" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

