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
Program to find the gcd of two number using function.
#Developed by: RAMYA R
#Register number: 212223230169
def gcd():
    num1,num2=int(input()),int(input())
    if num1<num2:
        smaller=num1
    else:
        smaller=num2
    for i in range (1,smaller+1):
        if num1%i==0 and num2%i==0:
            gcd1=i
    print("GCD of two numbers is:",gcd1)     
```
## Output:
![Screenshot 2024-04-14 194751](https://github.com/ramya23000505/GCD-of-two-numbers/assets/149370791/315478a3-5eba-4beb-bade-b23e8898edce)
![Screenshot 2024-04-14 194758](https://github.com/ramya23000505/GCD-of-two-numbers/assets/149370791/208fcd90-7967-4907-83b8-2cae5b8a4df7)
## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
