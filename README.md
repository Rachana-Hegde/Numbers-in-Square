Here’s a simple and clear **README.md** for your Python program that prints **numbers in a square pattern**:

---

# 🔢 Numbers in Square – Python Program

This is a beginner-level Python program that prints a **square pattern of numbers**, where each row contains repeated row numbers. It’s a great exercise for practicing nested `for` loops and understanding pattern printing.

## 📌 Description

* The user is asked to enter an integer `a`, which defines the **size of the square (a × a)**.
* The program prints `a` rows and `a` columns.
* Each row contains the same number repeated — corresponding to the current row number (starting from 1).

### 🧾 Sample Input & Output

**Input:**

```
Enter number: 4
```

**Output:**

```
1111  
2222  
3333  
4444  
```

## 🧠 Logic

* Use a nested `for` loop:

  * Outer loop for rows (`i`)
  * Inner loop for columns (`j`)
* In each row, print the value `i + 1` (so row count starts from 1).

## 🧾 Code

```python
a = int(input("Enter number: "))
for i in range(a):
    for j in range(a):
        print(i + 1, end="")
    print("")
```

## 🛠️ How to Run

1. Save the code in a file, e.g., `numbers_square.py`.
2. Run the script using Python:

```bash
python numbers_square.py
```

3. Enter a number when prompted, and the pattern will be displayed.

## 🎯 Use Case

* Good for **beginners** learning about:

  * Nested loops
  * Pattern-based logic
  * `print()` formatting

* Can be extended into more advanced number patterns like triangles, pyramids, etc.

## 📄 License

This code is available under the **MIT License**.
Feel free to use, share, and improve!

---

