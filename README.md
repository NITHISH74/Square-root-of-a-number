# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: NITHISHWAR S
RegisterNumber: 21002766

def newton_method(x, y = 100):

    a = float(x) 
    
    for i in range(y): 
    
        x = 0.5 * (x + a / x) 
        
    return x
    
a=int(input())


print("Square root of the number:",newton_method(a))
```

## Output:

![image](https://user-images.githubusercontent.com/94164665/146314915-393ab561-9ed4-4558-ab2e-7b14d26687ef.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
