# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Import numpy as np.
3. Using eval get the input matrix.
4. Declare the formula for lu decompostion and obtain the result.
5. End the program.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Devadhaarini.D
RegisterNumber: 212223230040
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: DEVADHAARINI.D
RegisterNumber: 212223230040
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://github.com/Devadhaarini/LU-Decomposition/assets/145796552/92ca32e7-2889-412d-bf6a-cdcad7f764ab)
![image](https://github.com/Devadhaarini/LU-Decomposition/assets/145796552/0c60249b-7ef3-4720-b99c-e13bc9f2ba62)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

