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
# Register No:23011258
# Developed By:Yendluri Chandana
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Chandana Yendluri
RegisterNumber: 23011258
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

```



# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/23011258/Norm-of-a-matrix/assets/139842204/642c6d64-02fc-40d3-9420-5189856ff031)


### 2-Norm of a Matrix
![image](https://github.com/23011258/Norm-of-a-matrix/assets/139842204/3f9944f4-2197-46aa-984c-8e7b3ac21e99)


### Infinity Norm of a Matrix
![image](https://github.com/23011258/Norm-of-a-matrix/assets/139842204/3607898e-3df9-43ef-9d6d-f51aeede8e9c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
