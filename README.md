# EX 2

### Name: STEFFI J
### Reg no: 212224220107

# 2a. Built-in Functions -Binary Conversion Using Built-in Functions in Python

## Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## Program

```
a=16
print(bin(a)
```

## Output

<img width="711" height="202" alt="image" src="https://github.com/user-attachments/assets/d0eec3ac-1b24-46ff-a471-8024fb1cf360" />


## Result

Thus,To write a Python program to convert the number 16 into its binary representation using built-in Python functions is executed successfully.

# 2b. Functions in Python: Modulo Calculator

## Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## Program

```
def result(a,b):
    c=print(a%b)
    return c
a,b=int(input()),int(input())
result(a,b)

```

## Output

<img width="661" height="206" alt="image" src="https://github.com/user-attachments/assets/50c0fb32-3971-4291-bd60-ac72c8c386d8" />


## Result

Thus,to write a Python program that defines a function which accepts two values and returns their modulo using the % operator is executed successfully.

# 2c. Lambda Function in Python: Addition of Two Numbers

## Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## Program

```
a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))
```

## Output

<img width="573" height="202" alt="image" src="https://github.com/user-attachments/assets/7615354f-2263-4526-8ae4-caa06b5f8c2c" />

## Result

Thus,to write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum is executed successfully.

# 2d.  Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

## Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

## Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

##  Program

```
r = int(input("Number of rows: "))
for n in range(r):
    print(" " * (r - n), end="")
    m = 1
    for k in range(n + 1):
        print(m, end=" ")
        m = m * (n - k) // (k + 1)
    print()  
```

## Sample Output

<img width="605" height="205" alt="image" src="https://github.com/user-attachments/assets/1e1a5920-9d87-4418-b08e-3e208fec8ea9" />


## Result

Thus,to write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is executed successfully.

# 2e. Loops in Python: Palindrome Number Checker

## Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## Program

```
num=int(input())
temp=num
rev=0
while temp>0:
   rev=(10*rev)+temp%10
   temp//=10
if num==rev:
   print("The given number is palindrome")
else:
   print("The given number is not a palindrime")
```

## Output

<img width="593" height="197" alt="image" src="https://github.com/user-attachments/assets/ac317685-7ced-459c-b757-d5dbd73c7b04" />

## Result

Thus,to write a Python program that checks whether a given number is a palindrome using loops is executed successfully.
