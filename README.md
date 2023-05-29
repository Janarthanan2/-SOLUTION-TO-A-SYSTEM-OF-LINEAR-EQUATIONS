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

      #Program to find the solution for the given linear equations.
      #Developed by: Janarthanan
      #RegisterNumber:212222230051
      import numpy as np
      A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
      B=np.array([-9,4,-1])
      sol=np.linalg.solve(A,B)
      print(sol)
      
## Output:
![Screenshot 2023-05-29 143347](https://github.com/Janarthanan2/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119393515/0f2a51d4-e0dd-44b7-8227-48fa523bbd20)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

