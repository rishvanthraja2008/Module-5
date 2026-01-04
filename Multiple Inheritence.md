# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
```
class py:
    def __init__ (self,a,b):
        self.a=a
        self.b=b
    def inh(self) :
        print(a)
        print(b)
        if c>80:
            print("Eligible for Module Exam")
        else:
            print("Not Eligible for Module Exam")


a=input()
b=int(input())
c=int(input())
obj=py(a,b)
obj.inh()

```
## Output Example
<img width="787" height="306" alt="image" src="https://github.com/user-attachments/assets/206bf10f-3362-437c-ae6f-3b4b56672b61" />

