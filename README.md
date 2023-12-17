# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```python
#Program to find the solution for the given linear equations.
#Developed by:aravindkumar ss 
#RegisterNumber:23004721

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
c=np.linalg.solve(a,b)
print(c)

```

## Output:
![image](https://github.com/aravindkumar23004721/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/148962674/8fb9a07e-4a15-45bb-aa17-1fe59b1426e9)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

