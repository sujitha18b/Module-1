## Experiment No: 1d – Conditional Statements- Even or Odd and greater than 25 or not

## AIM  

To write a Python program to check whether the given number is Even number and it is greater than or equal to 25 or not using nested if..else.

## ALGORITHM  

1. Take input from the user.

2.Check if the number is even (number % 2 == 0).

3.If yes, check if it's greater than or equal to 25.

4.If yes, print "Even and greater than or equal to 25".

5.Else, print "Even but less than 25".

6.Else, print "Odd number".



## PROGRAM

num = int(input( ))  <br />

if num % 2 == 0:   <br />
    print(f"{num} is an Even number")   <br />
    if num >= 25:   <br />
        print(f"{num} is greater than or equal to 25")   <br />
    else:   <br />
        print(f"{num} is lesser than 25")   <br />
else:   <br />
    print(f"{num} is NOT an Even number")



## OUTPUT

![Screenshot 2025-04-29 111515](https://github.com/user-attachments/assets/dd893169-a19d-4ac1-a073-abe7f12d3fbe)

## RESULT
Thus, the Python program to check whether the given number is Even number and it is greater than or equal to 25 or not using nested if..else. is implemented and executed sucessfully.
