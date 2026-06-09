# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Algorithm:
Algorithm for 1-Norm of a Matrix Step 1: Start the program.
Step 2: Import the necessary library (numpy).

Step 3: Read the input matrix from the user (evaluated as a nested list).

Step 4: Compute the 1-norm using the built-in function np.linalg.norm(matrix, 1).

Step 5: Format the calculated norm to two decimal places.

Step 6: Display the result.

Step 7: Stop the program.
Algorithm for 
L
2
-Norm of a Matrix Step 1: Start the program.
Step 2: Import the necessary library (numpy).

Step 3: Read the input matrix from the user.

Step 4: Compute the infinity norm using the built-in function np.linalg.norm(matrix, np.inf).

Step 5: Format the calculated norm to two decimal places.

Step 6: Display the result.

Step 7: Stop the program.
Algorithm for Infinity Norm of a Matrix
Step 1: Start the program.

Step 2: Import the necessary library (numpy).

Step 3: Read the input matrix from the user.

Step 4: Compute the infinity norm using the built-in function np.linalg.norm(matrix, np.inf).

Step 5: Format the calculated norm to two decimal places.

Step 6: Display the result.

Step 7: Stop the program

## Program:
```Python

'''
Developed By: RANJITH KUMAR R
RegisterNumber: 212224240131
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: RANJTH KUAMAR R
RegisterNumber: 212224240131
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix

'''
Developed by: RANJTH KUAMAR R
RegisterNumber: 212224240131
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))


```
## Output:
### 1-Norm of a Matrix
<img width="1047" height="845" alt="image" src="https://github.com/user-attachments/assets/bfee4b44-a280-4a4d-9824-d1da0017e025" />



### 2-Norm of a Matrix
<img width="970" height="952" alt="image" src="https://github.com/user-attachments/assets/6db458c8-c829-4d4a-8243-a96414e6cfae" />



### Infinity Norm of a Matrix
<img width="762" height="813" alt="image" src="https://github.com/user-attachments/assets/27f493dd-179d-4c99-9263-19745fec9624" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
