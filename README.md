# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a userdefined function
### Step 2: 
Get the input from the user using eval function
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the sliced list 
### Step 6: 
end of the program
## Program:
```
#Program to circulate N values.
#Developed by: vignesh v
#RegisterNumber: 23002301
def circulate():
    l=eval(input())
    n=int(input())
    o=l[n:]+l[:n]
    print("After circulating the values are:",o)
 ```   


## Output:
<img width="575" alt="image" src="https://github.com/Vigneshv-23/Circulate-the-values-of-N-variables/assets/110780412/9e798464-8d2c-4087-a92a-eaf2232b4c40">


## Result:
thus the numbers are circulated successfully
