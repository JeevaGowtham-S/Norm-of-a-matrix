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
# Register No:JEEVAGOWTHAM S
# Developed By:22008760
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
# Register No:JEEVAGOWTHAM S
# Developed By:22008760
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
# Register No:JEEVAGOWTHAM S
# Developed By:22008760
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot from 2023-01-26 13-30-15](https://user-images.githubusercontent.com/118042624/214785183-fb6f6f7b-90e8-4398-bad7-18f26c8074b4.png)
 
<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot from 2023-01-26 13-30-26](https://user-images.githubusercontent.com/118042624/214785306-cc41ca7b-8868-4995-a8bc-d27a523da86b.png)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot from 2023-01-26 13-30-35](https://user-images.githubusercontent.com/118042624/214785369-fb4baa0c-85e5-4da7-b9d8-0cabbc01fa68.png)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
