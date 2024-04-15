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
# Register No:212223230049
# Developed By:DILLIARASU M

# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,1)
print(f"{two_matrix:.2f}")

# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print(f"{two_matrix:.2f}")

# 3-Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,np.inf)
print(f"{two_matrix:.2f}")
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-14 170156](https://github.com/Dilliarasu0105/Norm-of-a-matrix/assets/144979593/a70cd336-5291-4d6c-aa0c-5eb8d54d950c)
### 2-Norm of a Matrix
![Screenshot 2024-04-14 170212](https://github.com/Dilliarasu0105/Norm-of-a-matrix/assets/144979593/16dbc61e-4f9b-4e81-b51a-a0ab617dd761)
###3-Infinity Norm of a Matrix
![Screenshot 2024-04-14 170227](https://github.com/Dilliarasu0105/Norm-of-a-matrix/assets/144979593/afe39dfd-f2ac-482b-9cde-123349de4850)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
