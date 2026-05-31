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
```num=int(input())
temp=num
rev=0
while(temp>0):
    rev=(10*rev)+temp%10
    temp=temp//10
if(num==rev):
    print("The number is a Palindrome")
else:
    print("The number is not a palindrome")
```
## Output
<img width="1919" height="799" alt="Screenshot 2026-05-31 183857" src="https://github.com/user-attachments/assets/9dc8ea67-bbf2-4838-aa4c-5f59988652fe" />

## Result
The given number was successfully checked using a loop.
It was correctly identified as a palindrome or not based on its reverse.
