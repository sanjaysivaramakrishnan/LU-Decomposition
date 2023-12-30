# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. import lu from scipy.linalg
3. use lu to find the value
4. print the value

## Program:
(i) To find the L and U matrix
```
/*
'''
Program to find L and U matrix using LU decomposition.
Developed by: Sanjay sivaramakrishnan M
RegisterNumber: 23013798
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
x,l,u=lu(a)
print(l)
print(u)
 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''
Program to solve a matrix using LU decomposition.
Developed by: Sanjay sivaramakrishnan M
RegisterNumber: 23013798
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x) 
*/
```

## Output:
![image](https://github.com/sanjaysivaramakrishnan/LU-Decomposition/assets/151629616/bdcc8c8d-78ad-4ec7-828c-256ec86676f3)
![image](https://github.com/sanjaysivaramakrishnan/LU-Decomposition/assets/151629616/edd5fb45-f63c-4ae0-9016-8afce919ddfb)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

