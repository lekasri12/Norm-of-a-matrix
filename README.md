# EX-07-Norm of a matrix
# DATE:
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
# Register No: 212223100025
# Developed By: G LEKA SRI
# 1-Norm of a Matrix
import numpy as np
matrix=eval(input())
norm=np.linalg.norm(matrix,1)
print(f"{norm:.2f}")




# 2-Norm of a Matrix
import numpy as np
matrix=eval(input())
norm=np.linalg.norm(matrix,2)
print(f"{norm:.2f}")





# Infinity Norm of a Matrix
import numpy as np
matrix=eval(input())
norm=np.linalg.norm(matrix,np.inf)
print(f"{norm:.2f}")





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-09-25 195444](https://github.com/user-attachments/assets/3948b30c-9410-4afe-88f4-34a0177319e2)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2024-09-25 195504](https://github.com/user-attachments/assets/4a6f04c7-06c2-43c3-9235-8b41e3abe040)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2024-09-25 195527](https://github.com/user-attachments/assets/7726fc84-bfd5-4429-ab21-e71079fead82)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
