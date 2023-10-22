# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(inpuut())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatenation operation display the entire rotated list
### Step 6:
stop the program
## Program:
```
#Program to circulate N values.
#Developed by: Goutham K
#RegisterNumber:23008975
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:
![image](https://github.com/Goutham2306/Circulate-the-values-of-N-variables/assets/138971154/9b7302c5-f456-49f9-a3c1-63d3593990dc)

## Result:
Thus the python for circulate the values of n variables is executed successfully.
