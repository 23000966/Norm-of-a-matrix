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

# 1-Norm of a Matrix
```
'''
program to find 1-norm of a matrix.
Developed by:SANTHOSH KUMAR R
Register number:212223240153
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: SANTHOSH KUMAR R
RegisterNumber: 212223240153
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```


# Infinity Norm of a Matrix
```
'''
Program to find Infinity-norm of a matrix.
Developed by: SANTHOSH KUMAR R
RegisterNumber: 212223240153
'''
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```


## output:

### 1-Norm of a Matrix
![image](https://github.com/23000966/Norm-of-a-matrix/assets/153983364/3699936e-39f1-4992-8295-73d96dab7277)

### 2-Norm of a Matrix
![image](https://github.com/23000966/Norm-of-a-matrix/assets/153983364/3377b2a2-d0dc-48c8-9bf5-afdd5c3add97)


### Infinity Norm of a Matrix
![Uploading image.png…]()

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
