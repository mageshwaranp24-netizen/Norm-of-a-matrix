# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## 1 NORM OF THE MATRIX:
## Step 1: Take the absolute value of each element in the matrix.
## Step 2: Find the sum of each column.
## Step 3: Compare all column sums.
## Step 4: The maximum column sum is the 1-norm.

## 2 NORM OF THE MATRIX:
## Step 1: Compute AᵀA (transpose of matrix × original matrix).
## Step 2: Find the eigenvalues of AᵀA.
## Step 3: Identify the largest eigenvalue.
## Step 4: Take the square root of it → this is the 2-norm.

## INFINITY NORM OF THE MATRIX:
## Step 1: Take the absolute value of each element in the matrix.
## Step 2: Find the sum of each row.
## Step 3: Compare all row sums.
## Step 4: The maximum row sum is the infinity norm.

## Program:
```Python
# Register No: 212225230161
# Developed By: MAGESHWARAN P
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (167)" src="https://github.com/user-attachments/assets/1490a300-abb5-49fd-b37f-0998ad682705" />


### 2-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot (168)" src="https://github.com/user-attachments/assets/bc91cb81-5dd8-4989-aef5-03b09037795d" />


### Infinity Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot (169)" src="https://github.com/user-attachments/assets/4a695411-5302-46f1-a47d-fe7c3dde0b64" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
