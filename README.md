# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import lu(),lu_factor() and lu_solve() from scipy.linalg library.
2. Use lu() method to find lower and upper matrix.
3. Use lu_factor() and lu_solve to solve the two matrixes.
4. End the program.

## Program:
(i) To find the L and U matrix '''Program to find L and U matrix using LU decomposition. Developed by: ANTONY ABISHEK RegisterNumber: 212223240009''' import numpy as np from scipy.linalg import lu matrix=np.array(eval(input())) pivot,l_matrix,u_matrix=lu(matrix) print(l_matrix) print(u_matrix) (ii) To find the LU Decomposition of a matrix '''Program to solve a matrix using LU decomposition. Developed by: ANTONY ABISHEK RegisterNumber: 212223240009'''

To print X matrix (solution to the equations)
import numpy as np import scipy.linalg as la A=np.array(eval(input())) B=np.array(eval(input())) LU,piv=la.lu_factor(A) x=la.lu_solve((LU,piv),B) print(x)


## Output:
![image](https://github.com/Antonyabishek2004/LU-Decomposition/assets/138849620/686906f3-a800-4097-8491-c6e6117defb3)
![EX NO 5 AI 2](https://github.com/Antonyabishek2004/LU-Decomposition/assets/138849620/67e56e6b-f3a5-475b-b116-0c01f6743811)
![image](https://github.com/Antonyabishek2004/LU-Decomposition/assets/138849620/4913f96f-e355-464b-aeab-5f762492d196)
![EX NO 5 AI 4](https://github.com/Antonyabishek2004/LU-Decomposition/assets/138849620/66916bf9-969e-40e4-b86b-787de77be75c)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

