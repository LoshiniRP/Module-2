## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
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

## 🧾 Program
```
num = input()
if num==num[::-1]:
    print("The given number", num, "is a Palindrome")
else:
    print("The given number", num, "is not a palindrome")
```

## Output
<img width="1006" height="202" alt="Screenshot 2025-10-18 194626" src="https://github.com/user-attachments/assets/4718161a-5f77-4dcc-a9e1-d1695870b9c9" />

## Result
Thus, the python program to check the given number is a palindrome or not has been executed successfully.
