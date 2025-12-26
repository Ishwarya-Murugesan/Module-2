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
n = int(input("Enter a number: "))
temp = n
rev = 0

while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10

if rev == n:
    print(n, "is a palindrome")
else:
    print(n, "is not a palindrome")
```
## Output
<img width="1920" height="1080" alt="Screenshot (120)" src="https://github.com/user-attachments/assets/1b562d88-3d20-4f57-9a79-75e3c8caa775" />

## Result
Thus, the program is executed successfully.
