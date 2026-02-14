---

Python Operators Demystified: Arithmetic, Logical, and Comparison Operators with Examples
Python operators are symbols used to perform operations on values and variables. They play a key role in writing Python programs because they help in performing calculations, comparing data, and making decisions based on conditions.
Operators work with operands (values or variables) to produce a result. Almost every Python program uses operators, which makes understanding them essential for beginners.

---

Arithmetic Operators
Arithmetic operators are used to perform mathematical operations such as addition, subtraction, multiplication, and division. These operators are commonly used in programs that deal with numbers like marks, prices, ages, and calculations.
a = 5
b = 2
print(a + b)   
print(a - b)   
print(a * b)   
print(a / b)   
print(a % b)   
print(a // b)  
print(a ** b)  
The division operator / always returns a decimal value, while // removes the decimal part and returns only the integer.

---

Comparison Operators
Comparison operators are used to compare two values. The result of a comparison is always either True or False. These operators are mainly used in conditional statements like if and else.
x = 10
y = 5
print(x == y)  
print(x != y)  
print(x > y)   
print(x < y)   
print(x >= y)  
print(x <= y)  
Comparison operators help the program decide which block of code should execute.

---

Logical Operators
Logical operators are used to combine multiple conditions into a single expression. Python provides three logical operators: and, or, and not.
age = 20
print(age > 18 and age < 30)
The and operator returns True only when both conditions are true.
marks = 40
print(marks >= 35 or marks == 0)
The or operator returns True if at least one condition is true.
is_active = False
print(not is_active)
The not operator reverses the result of the condition.

---

Combined Example
age = 22
if age >= 18 and age <= 60:
    print("Eligible")
else:
    print("Not Eligible")
This example uses comparison and logical operators together to make a decision.

---

Conclusion
Python operators form the foundation of programming logic. Arithmetic operators perform calculations, comparison operators evaluate conditions, and logical operators combine multiple checks. Understanding these operators helps beginners write correct and meaningful Python programs.
