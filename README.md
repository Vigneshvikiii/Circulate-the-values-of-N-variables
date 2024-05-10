# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
first step is to define the function
### Step 2: 
get a,n inputs from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
finally print the result

## Program:
~~~
def circulate():
    l=eval(input())
    n=int(input())
    n=n%len(l)
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
circulate()
~~~

## Output:

![Screenshot 2024-05-10 170846](https://github.com/Vigneshvikiii/Circulate-the-values-of-N-variables/assets/147474483/af35f931-8fc7-447d-b16c-a50bd4bf829f)

After circulating the values are: ['c', 'd', 'e', 'f', 'a', 'b']

## Result:
Thus circulating the variables in python is done and executed successfully.

