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

# 1-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: M HIMAVATH
RegisterNumber: 23010121
'''
import numpy as np
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,1)
ans="{:.2f}".format(norm)
print(ans)
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by:M HIMAVATH
RegisterNumber: 23010121
'''
import numpy as np 
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,2)
ans="{:.2f}".format(norm)
print(ans)
# Type your code here
```



# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by:M HIMAVATH
RegisterNumber: 23010121
'''
import numpy as np 
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,np.inf)
ans="{:.2f}".format(norm)
print(ans)

```



## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-24 215035](https://github.com/Himavath08/Norm-of-a-matrix/assets/139110631/4a8f21b9-2cea-4223-b628-cd259d78bddd)

### 2-Norm of a Matrix
![Screenshot 2023-12-24 215201](https://github.com/Himavath08/Norm-of-a-matrix/assets/139110631/616000d5-78d7-4c02-a8c4-c25a07709882)


### Infinity Norm of a Matrix
![Screenshot 2023-12-24 215209](https://github.com/Himavath08/Norm-of-a-matrix/assets/139110631/b286d7db-77c5-4ca7-a749-89fc8b8d9459)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
