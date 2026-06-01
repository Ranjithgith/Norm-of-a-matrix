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
# Register No: 212224240131
# Developed By:RANJITH R
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: DHARSHAN R
RegisterNumber: 212224230060
'''
import numpy as np
def find_1_norm(matrix_data):
    matrix = np.array(matrix_data)
    norm_1 = np.linalg.norm(matrix, ord=1)
    print(f"{norm_1:.2f}")
input_matrix = [[-1, 3], [3, -4], [1, 7]]
find_1_norm(input_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: RANJITH R
RegisterNumber: 212224240131
'''
import numpy as np

def calculate_l2_norm(matrix_data):
    matrix = np.array(matrix_data)
    l2_norm = np.linalg.norm(matrix, ord=2)
    return "{:.2f}".format(l2_norm)
test_1 = [[1, 2], [3, 4]]
test_2 = [[-1, 3], [3, -4], [1, 7]]
print(f"Input: {test_1} -> Result: {calculate_l2_norm(test_1)}")
print(f"Input: {test_2} -> Result: {calculate_l2_norm(test_2)}")



# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: RANJITH R
RegisterNumber: 212224240131
'''
import numpy as np
def matrix_infinity_norm(matrix_data):
    matrix = np.array(matrix_data)
    result = np.linalg.norm(matrix, ord=np.inf)
    return "{:.2f}".format(result)
input_data = [[-1, 3], [3, -4], [1, 7]]
print(matrix_infinity_norm(input_data)) 




```
## Output:
### 1-Norm of a Matrix
<img width="606" height="453" alt="image" src="https://github.com/user-attachments/assets/d14db6de-8eeb-4056-8d0d-30acbf7dc424" />


### 2-Norm of a Matrix
<img width="1049" height="491" alt="image" src="https://github.com/user-attachments/assets/c77034d9-4d99-4287-917e-76e246cb479c" />


### Infinity Norm of a Matrix
<img width="761" height="413" alt="image" src="https://github.com/user-attachments/assets/e0ab01f2-87e4-4779-b652-72b59df6215b" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
