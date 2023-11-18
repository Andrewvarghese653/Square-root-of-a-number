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
```python
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: ANDREW VARGHESE VS
RegisterNumber:  212222103001
*/
def newton_method(number,number_iters=100):
    a = float(number)
    for i in range(number_iters):
        number = 0.5*(number+a/number)
    return number 
a = int(input())
print("Square root of the number:",newton_method(a))

```

## Output:
<img width="839" alt="Screenshot 2023-11-18 at 8 46 48 AM" src="https://github.com/Andrewvarghese653/Square-root-of-a-number/assets/145822115/c8e49f41-78ad-49a3-8988-1b8dc648ae2b">

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
