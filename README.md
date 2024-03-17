# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the math module to use the built-in functions for calculations
### Step 2: 
Enter the coordinates of point one and two in the input
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the distance using the formula
### Step 5:
End the program 
### PROGRAM:
  ```
  import math
def dis(x1,x2,y1,y2):
    d=((x2-x1)**2+(y2-y1)**2) 
    g=math.sqrt(d)
    return g
x1=4
x2=10
y1=2
y2=6
g=dis(x1,x2,y1,y2)
print("{:.2f}".format(g))
  ```
  
### OUTPUT:
![alt text](<Screenshot (119).png>)

### RESULT:
Thus the program for Calculating the distance between two point are succesfully executed.