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
~~~
n=int(input())
for a in range(1,n):
    for b in range(a,0,-1):
        print(b,end=' ')
    print()
~~~
## Sample Output
<img width="369" height="447" alt="image" src="https://github.com/user-attachments/assets/4ab242af-7e3b-44ad-beeb-2032902e8fbf" />

## Result
Thus, the program has been successfully executed.
