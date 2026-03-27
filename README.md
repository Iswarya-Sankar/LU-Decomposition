# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. write a python code for the given matrix
2.using numpy libraries for lu decompositon
3.import scipy.linalg
4.and run the program
 

## Program:
(i) To find the L and U matrix
```

/*
Program to find the L and U matrix.

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

Developed by: Iswarya S
RegisterNumber: 212225040135
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

Developed by: Iswarya S
RegisterNumber: 212225040135
*/
```

## Output:
![lu decomposition]()
<img width="1011" height="780" alt="image" src="https://github.com/user-attachments/assets/1d708dad-c6d3-47e6-a868-30f826336793" />
<img width="1297" height="695" alt="image" src="https://github.com/user-attachments/assets/39890f0b-b24f-4566-b08f-98c0a10f2a40" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

