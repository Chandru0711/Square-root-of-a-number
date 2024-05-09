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
#Program to find the square root for the given number(newton's method) using function.
#Developed by: CHANDRU SM
#RegisterNumber: 212223230034
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp)) 
*/
```

## Output:

![Screenshot 2024-05-09 135500](https://github.com/Chandru0711/Square-root-of-a-number/assets/144979368/d93621f2-03e8-466c-8ff7-b437baf97c05)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
