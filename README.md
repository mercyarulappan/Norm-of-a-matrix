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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans= np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/mercyarulappan/Norm-of-a-matrix/assets/149233730/63961264-e7f6-4afd-ac8b-8c1041f8e2b4)
### 2-Norm of a Matrix
![image](https://github.com/mercyarulappan/Norm-of-a-matrix/assets/149233730/0d8f44a1-0e9d-4d5e-b7fc-924d26fb5cf6)
### Infinity Norm of a Matrix
![image](https://github.com/mercyarulappan/Norm-of-a-matrix/assets/149233730/5f7adc03-22c0-40e0-a1eb-8719b7bda923)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
