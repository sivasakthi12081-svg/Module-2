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
n=int(input("Enter number of rows: "))
for i in range(n):
    for j in range(n-i-1):
        print(" ",end="")
    num=1
    for j in range(i+1):
        print(num,end=" ")
        num=num*(i-j)//(j+1)
    print()
```

## Sample Output
<img width="1919" height="807" alt="Screenshot 2026-05-31 183419" src="https://github.com/user-attachments/assets/e423660f-7ef1-43c9-8612-8a1d3ff534e5" />

## Result
Pascal’s Triangle was successfully generated for the given number of rows.
Each row was printed correctly using the combination logic.
