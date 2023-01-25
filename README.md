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
# Register No:22008689
# Developed By:JAYAVARTHAN P
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix) 



# 2-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>


![Screenshot (18)](https://user-images.githubusercontent.com/121369281/214579900-87c7e800-7bcc-4045-a53f-73885cb3d5ae.png)



### 2-Norm of a Matrix
<br>
<br>
<br>


![Screenshot (19)](https://user-images.githubusercontent.com/121369281/214579958-20d04a68-34da-48ad-a09b-2c3a0149f313.png)


### Infinity Norm of a Matrix
<br>
<br>
<br>

![Screenshot (20)](https://user-images.githubusercontent.com/121369281/214580023-14cf41b8-e1d5-4dfa-85a4-d27901a1d722.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
