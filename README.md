# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

    ![eqn1](./ex4.jpg)

    ![eqn2](./ex6.jpg)

    ![eqn3](./ex3.jpg)

3.	Obtain the Q matrix   
    ![eqn4](./ex1.jpg)
4.	Construct the upper triangular matrix R
    ![eqn5](./ex2.jpg)



## Program:
### Gram-Schmidt Method
```
import numpy as np
a= np.array(eval(input()))
q,r= np.linalg.qr(a)
print(q)
print(r)






```
<img width="301" height="105" alt="image" src="https://github.com/user-attachments/assets/1bc6136a-122a-4f65-9ad8-5d4333cad2aa" />

## Output
```
[[-0.24253563 -0.9701425 ]
 [-0.9701425   0.24253563]]
[[-4.12310563 -5.33578375 -6.54846188]
 [ 0.         -0.72760688 -1.45521375]]
```

 <img width="364" height="111" alt="{86B6D372-A1C2-4173-8D43-BDD4247A0CC5}" src="https://github.com/user-attachments/assets/885149f7-4bf0-4c54-890b-82664e98d9e2" />

## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.
