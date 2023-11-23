# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function to circulate the values
### Step 2:
Get the value from the user for the number of values to circulate
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print n numbers of value it would be circulated
### Step 6:
End the program
## Program:
```
#Program to circulate N values.
#Developed by: SREEKUMAR S
#RegisterNumber:23008070
def circulate():
    l=eval(input())
    n=int(input())
    d=l[n:]+l[:n]
    print("After circulating the values are:",d)
```
## Output:
![circulate n values](https://github.com/guru14789/Circulate-the-values-of-N-variables/assets/151705853/ae5ab230-dda4-4d97-9532-45d671ca6bf4)


## Result:
Thus the circulate of N values are successfully executed
