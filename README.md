# DATE
# EX-05 LU Decomposition 

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
Program to find L and U matrix using LU decomposition.
Developed by: BHUVANESHWARI M
RegisterNumber: 212223230033
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: BHUVANESHWARI M
RegisterNumber: 212223230033
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2024-09-24 191705](https://github.com/user-attachments/assets/7278bb2f-0d12-4e35-9f84-3696b2b47f00)
![Screenshot 2024-09-24 191718](https://github.com/user-attachments/assets/8c7cf49e-56b3-4474-86f4-64571997c004)
![Screenshot 2024-09-24 191726](https://github.com/user-attachments/assets/6407e474-7fc1-4f91-8b4a-b0e79578b2e5)
![Screenshot 2024-09-24 191733](https://github.com/user-attachments/assets/f9dbbe45-c257-497d-af03-5e4faac4db9c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

