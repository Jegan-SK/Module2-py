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
    rows = int(input("Enter number of rows: "))

    for i in range(rows):
        # print spaces
        print(" " * (rows - i), end="")

        num = 1
        for j in range(i + 1):
            print(num, end=" ")
            num = num * (i - j) // (j + 1)

        print()

## Sample Output

<img width="1235" height="137" alt="image" src="https://github.com/user-attachments/assets/62a62dfc-2413-48cb-a113-2aa483b3d3e2" />


## Result

Thus the python program to generate a Pascal's Triangle, where the number of rows is provided by the user , is written and executed successfully .

