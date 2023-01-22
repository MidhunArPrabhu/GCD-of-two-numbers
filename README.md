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

![image](https://user-images.githubusercontent.com/118054670/213920219-e8fec56e-d5d6-4af9-9dd6-daa6b457f39c.png)

## OUTPUT :


![image](https://user-images.githubusercontent.com/118054670/213920255-0262ab85-f06f-460e-b5f2-e891bb7ecb8f.png)


## RESULT :

Thus the program to find the GCD of two numbers is written and verified using python programming.
