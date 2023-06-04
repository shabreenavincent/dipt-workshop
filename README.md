# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Shabreena Vincent
RegisterNumber:  212222230141
*/

def gcd():
    n1,n2=int(input()),int(input())
    if n1<n2:
        s=n1
    else:
        s=n2
    for i in range(1,s+1):
        if(n1%i==0 and n2%i==0):
            gcd=i
    print("GCD of two numbers is:",gcd)
```

## Output:




![gcd](https://github.com/shabreenavincent/GCD-of-two-numbers/assets/119475721/e822e0c9-eb01-4bb8-8260-4a68e43af3c9)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
