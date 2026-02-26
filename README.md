# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
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
