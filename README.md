# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 10 in the function to perform 10 iteratios.
3. Calculate  number = 0.5 * (number + a / number) for 10 iterations.
4. Get input from user,define assumption value.
5. Give function call.

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Sowmiya N
RegisterNumber:  21500134
*/

def root(x):
    for i in range(10):
        x=0.5*(x+b/x)
    print("Square root of the number:",x)
x=int(input())
b=x
root(x)
```

## Output:
![gcd of two number](py5.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
