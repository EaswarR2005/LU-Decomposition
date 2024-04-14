# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Write the code appropriately
3. Check the code
4. Run the program.

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: EASWAR.R
RegisterNumber: 212223230053
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: EASWAR.R
RegisterNumber: 212223230053
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
b=np.array(eval(input()))
sol=np.linalg.solve(matrix,b)
print(sol)
```
## Output:
(i) To find the L and U matrix

![image](https://github.com/EaswarR2005/LU-Decomposition/assets/146931525/f0b84fc2-0cd3-4422-a4c6-f3d4f09a71cf)
![image](https://github.com/EaswarR2005/LU-Decomposition/assets/146931525/1592a7be-8cac-4d6f-a88e-635fddc4f95c)

(ii) To find the LU Decomposition of a matrix
![image](https://github.com/EaswarR2005/LU-Decomposition/assets/146931525/0943fc67-7078-4e2d-a0fd-6db63e839ac7)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

