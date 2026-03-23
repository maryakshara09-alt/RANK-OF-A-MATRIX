# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.Start
2.Take the given matrix
3.Convert the matrix into row echelon form using row operations
4.Count the number of non-zero rows
5.That count is the rank of the matrix
6.Stop
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Mary Akshara S
#RegisterNumber:212225230169
#The number of linearly independent rows or coloumns in a
#matrix is known as its rank.
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
rank= np.linalg.matrix_rank(A)
print(rank)

```
## Output:
<img width="1920" height="1080" alt="Screenshot (249)" src="https://github.com/user-attachments/assets/76cc14c5-76dc-4143-8b8d-96279cb679ba" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

