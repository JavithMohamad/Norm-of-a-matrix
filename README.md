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
```
Python
# Register No:212222110014
# Developed By: JAVITH M
# 1-Norm of a Matrix
Program to find 1-norm of a matrix.

import numpy as np

mat = np.array(eval(input()))
ans =np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np

# Type your code here
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np

# Type your code here
mat = np.array(eval(input()))
ans =np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/JavithMohamad/Norm-of-a-matrix/assets/121215951/6edaebe9-d3b1-4637-97c7-090025701e07)


### 2-Norm of a Matrix
![image](https://github.com/JavithMohamad/Norm-of-a-matrix/assets/121215951/7d052cdd-007a-4569-8979-ce8c05e2f272)


### Infinity Norm of a Matrix
![image](https://github.com/JavithMohamad/Norm-of-a-matrix/assets/121215951/2a6ce6c5-06a9-4710-a62f-738205cef412)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
