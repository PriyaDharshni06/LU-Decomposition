# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## (i):
1. Import the numpy module and lu module from scipy.linalg to use the built-in
functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the lu(), we get three results (first is P, second is L and third is U) of the given
matrix.
4. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the
variable as 'X' include the package in that variable.
5. End the program
## (ii):
1.Start

2.Input the matrix A and vector b

3.Use LU Decomposition to factor the matrix A into L (lower triangular) and U (upper triangular)
→ Use lu_factor(A)

4.Solve the equation Ax = b using the LU factors
→ Use lu_solve((lu, piv), b)

5.Print the solution vector x

6.End


## Program:
```PYTHON
(i) To find the L and U matrix

Program to find the L and U matrix.
Developed by:PRIYA DHARSHNI S
RegisterNumber: 212224100045

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)


(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.
Developed by: PRIYADHARSHNI S
RegisterNumber: 212224100045

import numpy as np
from scipy.linalg import lu_factor, lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(a)
x = lu_solve((lu, piv), b)
print(x)

```
## Output:
![Screenshot 2025-05-17 153034](https://github.com/user-attachments/assets/61f42318-1a40-4b4e-bf94-e0c9ee2fc362)

![Screenshot 2025-05-17 153049](https://github.com/user-attachments/assets/d7784cc7-8e27-49ee-b827-f1683f2aa62f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

