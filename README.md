# Python Integer Division Program

## 📌 Overview

This project is a simple Python program that accepts two integers from the user and performs **integer division** using the floor division operator (`//`).

The program demonstrates basic Python concepts such as:

* User input
* Variables
* Arithmetic operators
* Output formatting

This is an ideal beginner project for understanding how Python handles arithmetic operations.

---

## 🚀 Features

* Accepts two integer inputs from the user
* Performs integer (floor) division
* Displays the division result
* Beginner-friendly implementation

---

## 🛠️ Technologies Used

* Python 3

---

## 📂 Project Structure

```text id="8rm6uk"
├── division_program.py
└── README.md
```

---

## 💻 Source Code

```python id="pdhqpd"
print("Program starts...")

a = int(input("Enter first number : "))
b = int(input("Enter second number : "))

c = a // b

print("The division of", a, "and", b, "is", c)

print("Program ends...")
```

---

## ▶️ How to Run

### Clone the Repository

```bash id="n2mkab"
git clone https://github.com/your-username/python-division-program.git
cd python-division-program
```

### Run the Program

```bash id="z0x7wv"
python division_program.py
```

---

## 📋 Sample Output

### Example 1

```text id="5wldee"
Program starts...
Enter first number : 20
Enter second number : 5
The division of 20 and 5 is 4
Program ends...
```

### Example 2

```text id="yg0k39"
Program starts...
Enter first number : 17
Enter second number : 4
The division of 17 and 4 is 4
Program ends...
```

---

## 🧠 Concepts Covered

* Python Input and Output
* Variables
* Integer Data Type
* Arithmetic Operators
* Floor Division (`//`)

---

## 🔍 Understanding `//`

The operator:

```python id="k3nkho"
a // b
```

performs **floor division**, which returns only the integer part of the result.

Examples:

```text id="ktj2o5"
20 // 5 = 4
17 // 4 = 4
10 // 3 = 3
```

---

## ⚠️ Note

This program does not include exception handling.

Possible errors:

* Entering non-numeric input (`ValueError`)
* Dividing by zero (`ZeroDivisionError`)

These can be handled using `try-except` blocks in future versions.

---

## 🔮 Future Improvements

* Add exception handling
* Support floating-point division
* Build a menu-driven calculator
* Add more arithmetic operations
* Create a GUI version using Tkinter

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How to take user input in Python
* How arithmetic operators work
* The difference between `/` and `//`
* How to display formatted output

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer
Aspiring Software Engineer | Python | SQL | Data Analytics

---

## 📄 License

This project is open-source and available for educational and learning purposes.

<img width="639" height="797" alt="image" src="https://github.com/user-attachments/assets/54022e1e-015a-4458-b547-0763c41b6d48" />
