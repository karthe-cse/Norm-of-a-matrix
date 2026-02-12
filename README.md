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
# Register No:25017571
# Developed By:KARTHEESHWAR D J
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
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="1202" height="227" alt="image" src="https://github.com/user-attachments/assets/0f5f2e58-3198-4f8d-9961-062aefa7e40a" />


### 2-Norm of a Matrix
<img width="1200" height="261" alt="Screenshot 2026-02-12 135154" src="https://github.com/user-attachments/assets/42e721d5-2f20-4733-b029-7890dbae65f9" />


### Infinity Norm of a Matrix
<img width="1299" height="230" alt="Screenshot 2026-02-12 135119" src="https://github.com/user-attachments/assets/74a34e8e-2130-4cc3-b560-cc3559b8f2ba" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
