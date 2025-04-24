# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Input the coefficient matrix A and the right-hand side vector b.
### Step 2: Perform LU decomposition using lu_factor(A) to get LU matrix and pivot indices.
### Step 3: Use lu_solve((lu, piv), b) to solve the system Ax = b.
### Step 4: Print the solution vector x.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MARIMUTHUMATHAVAN
RegisterNumber: 212224230153
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,L,U=lu(A)
print(L)
print(U)
```

## Algorithm
### Step 1: Input the coefficient matrix A and the right-hand side vector b.
### Step 2: Perform LU decomposition using lu_factor(A) to get LU matrix and pivot indices.
### Step 3: Use lu_solve((lu, piv), b) to solve the system Ax = b.
### Step 4: Print the solution vector x.

## Program
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MARIMUTHU MATHAVAN 
RegisterNumber: 212224230153
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2025-04-24 210804](https://github.com/user-attachments/assets/7bf1134e-b1df-4b7c-8ad5-2be48fde64a4)
![Screenshot 2025-04-24 210825](https://github.com/user-attachments/assets/36a7892b-ab54-4170-9a56-d20d277da45c)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

