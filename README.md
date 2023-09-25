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
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SARAVANA KUMAR M
RegisterNumber: 212222230133
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SARAVANA KUMAR M 
RegisterNumber: 212222230133
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

```

## Output:
![Screenshot 2023-09-25 105503](https://github.com/Saravana-kumar369/LU-Decomposition/assets/117925254/4f9fd92c-c5f4-4ba1-a0d5-c7c85357cda4)

![Screenshot 2023-09-25 105718](https://github.com/Saravana-kumar369/LU-Decomposition/assets/117925254/f4218d31-aa21-4abe-a55a-6cb3c214259d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

