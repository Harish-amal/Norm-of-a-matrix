# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	Step 1.
	
	Get the input matrix using np.array()   
    
	Step 2. 
	
	Find the 2-norm of the matrix using np.linalg.norm()
	
	Step 3. 
	
	Print the norm of the matrix in two decimal places.
	
## Program:
```Python
# Register No: 26014406
# Developed By: Harish amal S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<img width="1222" height="798" alt="image" src="https://github.com/user-attachments/assets/22a8578a-efb3-473e-886a-3122f512b25f" />

<br>

### 2-Norm of a Matrix
<img width="1220" height="836" alt="image" src="https://github.com/user-attachments/assets/f5a3ceac-25d8-480d-b882-645ad7b0d191" />

<br>

### Infinity Norm of a Matrix
<img width="1222" height="801" alt="image" src="https://github.com/user-attachments/assets/cf0edee9-208c-46bb-b6d9-407d8987c368" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
