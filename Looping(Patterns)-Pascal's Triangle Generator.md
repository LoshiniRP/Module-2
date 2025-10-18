# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

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

---

## 🧪 Program
```
n = int(input())
c = 1
for i in range(1, n+1):
    for j in range(1, n-i+1):
        print(" ", end="")
    for j in range(0, i):
        if j==0 or i==0:
            c=1
        else:
            c = c*(i-j)//j
        print(c, end=" ")
    print()
```

## Sample Output
<img width="555" height="559" alt="Screenshot 2025-10-18 194436" src="https://github.com/user-attachments/assets/2c103212-ffc6-4fc3-bd76-b6a78d5c9109" />

## Result
Thus the python program to generate Pascals's triangle has beem executed successfully.
