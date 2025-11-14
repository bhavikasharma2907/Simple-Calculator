# Simple-Calculator
# Python Simple Calculator

A command-line calculator script written in Python. It performs addition, subtraction, multiplication, and division on two numbers based on user input.

---

## How to Use

1. **Save the script** in a file named `calculator.py`.
2. **Run the script** using your terminal or command prompt:

    ```
    python calculator.py
    ```

3. **Follow the on-screen prompts:**
   - Enter the first number
   - Enter the second number
   - Enter the operation you want (`+`, `-`, `*`, `/`)

---

## Example

enter 1st number: 15
enter 2st number: 5
enter your choice : /
3.0

text

---

## Source Code

a = int(input("enter 1st number"))
b = int(input("enter 2st number"))
choice = input("enter your choice ")

if choice == "+":
print(a + b)
elif choice == "-":
print(a - b)
elif choice == "*":
print(a * b)
elif choice == "/":
print(a / b)
else:
print("invalid choice")
