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
```
#Program to find 2-norm of a matrix.
#Developed by:A.BHAGATHKRISHNA
#RegisterNumber: 23002963
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
```
#Program to find 2-norm of a matrix.
#Developed by:A.BHAGATHKRISHNA
#RegisterNumber: 23002963
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by:A.BHAGATHKRISHNA
RegisterNumber: 23002963
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```





```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-12-29 044144](https://github.com/Bhagath118/Norm-of-a-matrix/assets/147473779/b1abf033-e103-468f-bac4-d3ba632743dd)


### 2-Norm of a Matrix

![Screenshot 2023-12-29 044157](https://github.com/Bhagath118/Norm-of-a-matrix/assets/147473779/8b62f143-86d5-4764-89d6-165a94d0f789)



### Infinity Norm of a Matrix


![Screenshot 2023-12-29 044220](https://github.com/Bhagath118/Norm-of-a-matrix/assets/147473779/da0aff26-edf3-407e-b8cf-627e0f4bdfd5)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
