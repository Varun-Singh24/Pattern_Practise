# 🧩 Pattern Practice in Python (Jupyter Notebook)

This repository contains Python programs for practicing **pattern printing**, written and executed in a **Jupyter Notebook**.  
Pattern problems help strengthen **loop logic**, **nested loops**, and **string manipulation**.
---

## 🛠️ Tools & Environment

- **Language:** Python 🐍  
- **Environment:** Jupyter Notebook  
- **Concepts Used:**  
  - for loops  
  - nested loops  
  - string multiplication  
  - user input  

---

## ⭐ Star Pattern

### 📌 Pattern
```

*
* *

````

### 🧾 Code
```python
for i in range(1, 5 + 1):
    for j in range(i):
        print('* ', end='')
    print()
````

### 🎯 Use Case

✔ Understanding nested loops
✔ Building blocks for complex patterns

---

## 🔢 Number Pyramid Pattern

### 📌 Pattern

```
1
121
12321
1234321
```

### 🧾 Code

```python
for i in range(1, 5):
    for j in range(i):
        print(j + 1, end='')
    for j in range(i - 1, 0, -1):
        print(j, end='')
    print()
```

### 📘 Explanation

* First loop prints increasing numbers
* Second loop prints decreasing numbers
* Combines two loops to form a symmetric pattern

### 🎯 Use Case

✔ Interview pattern problems
✔ Logical thinking with loops

---

## 🪜 Staircase Star Pattern (Right-Aligned)

### 📌 Pattern

```
    *
   **
  ***
 ****
```

### 🧾 Code (Using User Input)

```python
n = int(input("Enter n: "))

for i in range(1, n):
    for j in range(n - i, 0, -1):
        print(" ", end='')
    for k in range(i):
        print('*', end='')
    print()
```

### 📘 Explanation

* First loop prints spaces
* Second loop prints stars
* Creates right-aligned staircase effect

### 🎯 Use Case

✔ Alignment-based pattern logic
✔ Competitive programming problems

---

## 🧱 Staircase Pattern Using String Multiplication

### 📌 Pattern

```
      #
     ##
    ###
   ####
  #####
```

### 🧾 Code

```python
n = 5
for i in range(1, n + 1):
    print(" " * (n - i) + "#" * i)
```

### 📘 Explanation

* `" " * (n - i)` creates leading spaces
* `"#" * i` prints required characters
* Cleaner and more Pythonic approach

### 🎯 Use Case

✔ Writing optimized code
✔ Improving Python readability

---

## 🧠 Concepts Practiced

* Nested loops
* Loop control
* Pattern alignment
* String repetition
* Input handling

---

⭐ If you find this helpful, consider starring the repository!

 🚀
