# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
import numpy as np

Step 2:
from scipy package import lu

Step 3:
get input from the user

Step 4:
print result

## Program:
/*

Developed by: Ashish S

RegisterNumber: 212224240017

*/
(i) To find the L and U matrix
```
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor ,lu_solve
a=eval(input())
b=eval(input())
lu,plv=lu_factor(a)
x=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![image](https://github.com/user-attachments/assets/cc92e14c-bc86-4258-a342-54813d906603)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/user-attachments/assets/aee0fb91-e0f5-48ca-b521-3045fe85ceb0)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

