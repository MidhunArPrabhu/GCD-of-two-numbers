# FIND THE GCD OF TWO NUMBERS :

## AIM :

To write a program to find the GCD of two numbers using function.

## EQUIPMENTS REQUIRED :

- Hardware – PCs  
- Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHIM :

1. Define a function. 
2. Get the two numbers from the user.  
3. Compare the two values, to find the smaller number.  
4. Use for() and if() loop to find the GCD of the two numbers.  

## PROGRAM :

```

Program to find the gcd of two number using function.
Developed by: MIDHUN AZHAHU RAJA P
RegisterNumber: 22008311

def gcd():
   n=int(input())
   m=int(input())
   if(n>m):
      min=m
   else:
      min=n
   for i in range(1,min+1):
       if(n%i==0 and m%i==0):
           o=i
   print("GCD of two numbers is:",o)           
       
```

## GIVEN INPUT : 

![Screenshot_20230122_072954](https://user-images.githubusercontent.com/118054670/213920063-4a173887-2925-4130-808f-43d5dafbe3e3.png)


## Output:


![Screenshot_20230122_073036](https://user-images.githubusercontent.com/118054670/213920076-e90549d5-f541-4a3e-b9ce-419782d5a1d6.png)


## RESULT :

Thus the program to find the GCD of two numbers is written and verified using python programming.
