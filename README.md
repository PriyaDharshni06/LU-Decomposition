# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module and lu module from scipy.linalg to use the built-in
functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the lu(), we get three results (first is P, second is L and third is U) of the given
matrix.
4. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the
variable as 'X' include the package in that variable.
5. End the program

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
![Screenshot 2025-04-26 092103](https://github.com/user-attachments/assets/1309824d-7539-4434-9ab9-72cab445f19a)


![Screenshot 2025-04-26 092122](https://github.com/user-attachments/assets/fa306b00-4a17-4696-9fae-2a5610316c80)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

