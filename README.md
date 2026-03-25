
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
# Register No: 212224230207
# Developed By: PRAVEEN RAJ R
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="1340" height="727" alt="image" src="https://github.com/user-attachments/assets/daf26a63-432e-40af-bf3d-4158cef26d3c" />



### 2-Norm of a Matrix
<img width="1307" height="542" alt="image" src="https://github.com/user-attachments/assets/ac7042f2-d029-485a-8587-2f4e3bfb7191" />


### Infinity Norm of a Matrix

<img width="1352" height="686" alt="image" src="https://github.com/user-attachments/assets/5eb68059-0c66-4401-8acf-9ac6b844f882" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
