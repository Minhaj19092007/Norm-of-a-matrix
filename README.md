# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	 1-norm:
	
	1.Get the input matrix using np.array()
    2.Compute column-wise absolute sum using np.sum(abs(A), axis=0)
    3.Find the maximum value among the column sums → that is 1-norm
    4.Print the norm value in two decimal places
	
	2-norm:
	
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

	Infinity norm:
	
    1.Get the input matrix using np.array()
    2.Compute row-wise absolute sum using np.sum(abs(A), axis=1)
    3.Find the maximum value among the row sums → that is infinity norm
    4.Print the norm value in two decimal places
## Program:
```Python
# Register No:212225230135
# Developed By:KAVIRAJ.P
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="874" height="627" alt="Screenshot 2026-02-23 182839" src="https://github.com/user-attachments/assets/c7e6a73d-2436-43a5-9789-aefef58aa93d" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="873" height="630" alt="Screenshot 2026-02-23 182952" src="https://github.com/user-attachments/assets/fcde1674-b652-41b1-88f6-ad9cec3b3025" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="874" height="631" alt="Screenshot 2026-02-23 183028" src="https://github.com/user-attachments/assets/146ffb6d-4c43-497f-bafd-397b1dca3761" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
