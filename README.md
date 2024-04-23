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
# Register No:212223230037
# Developed By:Darius Rijin I
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Darius Rijin I 
RegisterNumber: 212223230037
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
![Maths 1](https://github.com/DariusRijin07/Norm-of-a-matrix/assets/138849120/83e115cb-c289-49d6-bbdc-5d3aef123b52)


### 2-Norm of a Matrix

![Maths 2](https://github.com/DariusRijin07/Norm-of-a-matrix/assets/138849120/71419618-7954-4d73-b4aa-04cdcd4fb5ea)

### Infinity Norm of a Matrix
![Maths 3](https://github.com/DariusRijin07/Norm-of-a-matrix/assets/138849120/acebc7dc-75e4-4741-aece-8b90d7f9eef9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
