# Multiplying-two-matrix

## AIM:
To find the product of two arrays using numpy by using python programming.
## ALGORITHM:

### Step 1:
Import Numpy as np.
### Step 2:
Get input from the user.
### Step 3:
Create empty lists l1 and l2.
### Step 4:
Use for loop to append the values into the list created.
### Step 5:
Print the product of two arrays.

## PROGRAM: 
import numpy as np
l1,l2=[],[]
n=int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
array_1=np.array(l1)
array_2=np.array(l2)
product=array_1*array_2
print("Product of two arrays is:",product)

## OUTPUT:
![image](https://user-images.githubusercontent.com/94505585/154469975-96240515-97b0-4a8e-b11a-eb0ba8d0318f.png)


## RESULT:
Thus the program to find the product of two arrays using numpy has been verfied successfuly using python programming.

