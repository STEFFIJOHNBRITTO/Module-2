#  Looping(Patterns)-Pascal's Triangle Generator in Python

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
