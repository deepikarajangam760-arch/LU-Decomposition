# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the necessary libraries(numpy,scipy.linalg)
2. Define the matrix using numpy
3. Use lu(),lu_solve(),lu_factor() to get the solutions
4. End the program

## Program:
(i) To find the L and U matrix

'''Program to find L and U matrix using LU decomposition.

Developed by: R.DEEPIKA

RegisterNumber: 25016530
'''

import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix

'''Program to solve a matrix using LU decomposition.

Developed by: R.DEEPIKA

RegisterNumber: 25016530

'''

import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,pivot=lu_factor(A)

x=lu_solve((lu,pivot),B)

print(x)

## Output:

<img width="1293" height="786" alt="image" src="https://github.com/user-attachments/assets/debde867-aed9-4ff7-a9ad-8007dcbd25b0" />
<img width="1336" height="593" alt="image" src="https://github.com/user-attachments/assets/5db0cffa-09a1-4f2f-9c8f-6eb5660586b6" />
<img width="1438" height="834" alt="image" src="https://github.com/user-attachments/assets/400afede-3de6-4a7b-ad1c-a14da6f26ac8" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

