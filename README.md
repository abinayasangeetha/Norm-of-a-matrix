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
# Register No:ABINAYA S
# Developed By:212222230002
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)




# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))



# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)





```
## Output:
### 1-Norm of a Matrix
![norm1](https://github.com/abinayasangeetha/Norm-of-a-matrix/assets/119393675/4c079065-7e81-4bcb-83ef-3063b7583a78)


### 2-Norm of a Matrix
![norm2](https://github.com/abinayasangeetha/Norm-of-a-matrix/assets/119393675/8a1e293a-8531-4654-b98d-54f9fdd9e5db)


### Infinity Norm of a Matrix
![infinity norm](https://github.com/abinayasangeetha/Norm-of-a-matrix/assets/119393675/36967965-566c-4858-9550-4c66a6577e11)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
