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
# Register No:212224110048
# Developed By: Sitharth B S
# 1-Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,1)
print("{:2f}".format(norm))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm)) 


# Infinity Norm of a Matrix

import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm)) 



```
## Output:
### 1-Norm of a Matrix
<img width="1905" height="955" alt="image" src="https://github.com/user-attachments/assets/3405367b-c3da-46a8-890b-b72f59a6c4ef" />


### 2-Norm of a Matrix
<img width="1496" height="949" alt="image" src="https://github.com/user-attachments/assets/85e5004f-1013-4116-a126-88bc8eeb2c62" />


### Infinity Norm of a Matrix
<img width="1502" height="951" alt="image" src="https://github.com/user-attachments/assets/39d2703c-4afe-4f2c-b7c9-4632b23a7b9b" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
