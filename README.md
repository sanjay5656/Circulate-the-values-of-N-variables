# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the list values from the user.
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list.
### Step 4: 
To print the circulate value.
### Step 5: 
End program.
## Program:
```
Program to circulate N values.
Developed by: Sanjay S
RegisterNumber: 212221243002
```
```
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n: ]+a[ :n]
    print('After circulating the values are:',a)
```
## Output:
# Before:
![Screenshot 2023-08-24 192318](https://github.com/sanjay5656/Circulate-the-values-of-N-variables/assets/115128955/ad08c37a-dd72-4ce3-9050-30e89f47ad0f)
# After:
![Screenshot 2023-08-24 192328](https://github.com/sanjay5656/Circulate-the-values-of-N-variables/assets/115128955/92e26f59-f26f-4cc6-b97c-4939a4e912b7)
## Result:
Thus the circulating values are successfully executed. 
