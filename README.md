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
# Register No: 212224240044
# Developed By: Gokul S
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-23 180340](https://github.com/user-attachments/assets/a771a73a-0f69-4937-b92d-46af4e0fe9d5)


### 2-Norm of a Matrix
![Screenshot 2025-04-23 180417](https://github.com/user-attachments/assets/9acfd3e5-caf9-408b-8339-ec0d679affa5)


### Infinity Norm of a Matrix
![Screenshot 2025-04-23 180434](https://github.com/user-attachments/assets/e0b44dfa-3ee8-48b1-b5af-c21c84871390)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
