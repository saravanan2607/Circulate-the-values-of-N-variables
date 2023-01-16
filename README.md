# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Using a function Circulate.
 
### Step 2:
create two variables as eval and int data type.

### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.

### Step 5:
Give the print statement .

### Step 6:
End of Program 

## Program:
``` py
#Program to circulate N values.
#Developed by: C Saravanan
#RegisterNumber: 22008175
def circulate():
    l=eval(input())
    n=int(input())
    L=l[n:] + l[:n]
    print("After circulating the values are:",L)


```

## Output:
![Output](/Screenshot%20from%202023-01-10%2021-09-45.jpg)

## Result:
thus, the Circulate the values of N variables is successfully executed.