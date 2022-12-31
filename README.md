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

Program to find the gcd of two number using function.
Developed by:B.Bejin 
RegisterNumber: 22001908 
```
## Program:
def gcd():
    a,b=int(input()),int(input())
    if a>b:
        smaller=b
    else:
        smaller=a
    for i in range(1,smaller+1):
        if(a%i==0 and b%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![image](https://user-images.githubusercontent.com/118367518/210138123-1cbcc701-d741-4a8a-be97-a7b7a286ec49.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
