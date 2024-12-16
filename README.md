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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```

## Output:
![Screenshot 2024-12-16 184037](https://github.com/user-attachments/assets/9bd299c6-5725-4bd3-b757-6be5ee15be67)
![Screenshot 2024-12-16 184058](https://github.com/user-attachments/assets/a087ff55-82a3-4171-ab2d-f9533d58b34e)
![Screenshot 2024-12-16 184117](https://github.com/user-attachments/assets/828451b9-935b-4377-9e3e-e6caee585062)






## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
