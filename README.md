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
#Square root of a number
#Developed by: ponguru aasrith sairam
#Register number: 23007809
def newton_method(number,num=100):
    a=float(number)
    for i in range(num):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![fotor_2023-7-23_20_14_2-fotor-20230723201832](https://github.com/AasrithSairam/Square-root-of-a-number/assets/139331438/1997dee5-23dc-4a04-a9bb-516307ac3cbd)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
