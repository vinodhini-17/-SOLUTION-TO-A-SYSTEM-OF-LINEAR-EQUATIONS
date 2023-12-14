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
``````
import numpy as np
A=[[1,-3],[3,1]]
B=[0,10]
C=np.linalg.solve(A,B)
print(C)
``````
## Output:
![solve](https://github.com/vinodhini-17/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145742741/197aabad-401d-4662-80e0-944543846349)




## Result: 
Thus the solutions for the linear equations are successfully solved using python program

