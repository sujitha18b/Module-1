# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).



## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.



## PROGRAM

a = float(input())         <br />
b = float(input())         <br />
c = float(input())         <br />
if (a<b)and(a<c):          <br />
    print(f"The minimum of {a}, {b}, {c} is {a}")    <br />
elif (b<c)and(b<a):      <br />
    print(f"The minimum of {a}, {b}, {c} is {b}")  <br />
else:   <br />
    print(f"The minimum of {a}, {b}, {c} is {c}")

## OUTPUT

![Screenshot 2025-04-29 112225](https://github.com/user-attachments/assets/210b4693-f83d-44f7-9fd9-b12edb4ebdd9)


## RESULT
Thus,the given python program is implemented and the output is verified.
