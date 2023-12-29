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
ans=np.linalg.norm(mat,2)
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

![Screenshot 2023-12-29 044144](https://github.com/Bhagath118/Norm-of-a-matrix/assets/147473779/4f09a4e9-eff3-4746-9cb8-50fa9999f063)




### 2-Norm of a Matrix

![Screenshot 2023-12-29 044157](https://github.com/Bhagath118/Norm-of-a-matrix/assets/147473779/7789e804-366f-4cde-898b-d76556f5e24f)





### Infinity Norm of a Matrix


![Screenshot 2023-12-29 044220](https://github.com/Bhagath118/Norm-of-a-matrix/assets/147473779/5513f0c6-f723-4f87-bb64-728af34cb69d)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
