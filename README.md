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
# Register No:22000990
# Developed By:M Srinath
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: M Srinath
RegisterNumber: 22000990
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)






# Infinity Norm of a Matrix
Developed by: M Srinath
RegisterNumber: 22000990
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)





```
## Output:
![Screenshot from 2023-01-25 23-52-24](https://user-images.githubusercontent.com/118678482/214649707-b2c0c0de-2e5c-4e04-8510-2b3cd614fe22.png)


### 2-Norm of a Matrix
![Screenshot from 2023-01-25 23-53-27](https://user-images.githubusercontent.com/118678482/214649940-a7b3528e-ec71-445b-b81e-cce58c346d71.png)



### Infinity Norm of a Matrix
![Screenshot from 2023-01-25 23-54-00](https://user-images.githubusercontent.com/118678482/214650077-801183b6-139b-4148-8dc7-52289ac5c165.png)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
