# Multiplying-two-matrix

## AIM:
To write a python program to multiply two arrays using numpy.

## ALGORITHM:
### Step 1:
Import the numpy as np.

### Step 2:
Create a two list and enter the count of the array.

### Step 3:
Using the for loop append the entries in two lists.

#### Step 4:
After add the all values multiply the two lists.

### Step 5:
Print the product of the two array.


## PROGRAM: 
```
import numpy as np
n=int(input())
l1,l2=[],[]
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1=np.array(l1)
value2=np.array(l2)
s=value1*value2
print("Product of two arrays is:",s)
```
## OUTPUT:
![multi](https://user-images.githubusercontent.com/94170892/153348981-d244567d-c00f-44d4-a73c-9767c488b15f.png)

## RESULT:
The above program is successfully to multiply two arrays using numpy.
