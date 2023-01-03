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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Shakthi kumar S
RegisterNumber: 22009242
*/
```
```python
a=int(input())
def square_root(b,l=100):
    a=float(b)
    for i in range(l):
        b=0.5*(b+a/b)
    return b
print("Square root of the number:",square_root(a))
```


## Output:
![gcd of two number](gcd.png)
![](Exp%2005.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
