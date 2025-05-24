# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Start the program.
### Step 2: Import numpy as np.
### Step 3: Accept the matrix from the user using input().
### Step 4: Convert it into a NumPy array using eval() and np.array().
### Step 5: Use the lu() function to decompose the matrix into three matrices: permutation matrix P, lower triangular matrix L, and upper triangular matrix U.
### Step 6: Store the L matrix returned by the lu() function.
### Step 7: Print the lower  and Upper matrix L.
### Step 8: End the program.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MARIMUTHU MATHAVAN
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
### Step 1: Start the program.
### Step 2: Import numpy as np and import lu_factor, lu_solve from scipy.linalg.
### Step 3: Read the matrix A from the user using input() and convert it to a NumPy array.
### Step 4: Read the right-hand side vector b using input() and convert it to a NumPy array.
### Step 5: Use lu_factor(A) to compute the LU decomposition and pivoting information of matrix A.
### Step 6: Use lu_solve((lu, piv), b) to compute the solution vector x.
### Step 7: Display the result using print(x).
### Step 8: End the program.
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

