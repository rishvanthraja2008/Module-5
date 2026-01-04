# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
class py:
    def __init__ (self,a,b):
        self.a=a
        self.b=b
    def inh(self)    :
        print(a)
        print(b)
        if c>12000:
            print("Valid Student")
        else:
            print("Invalid Student")


a=input()
b=int(input())
c=int(input())
obj=py(a,b)
obj.inh()
```
## Sample Output
<img width="678" height="295" alt="image" src="https://github.com/user-attachments/assets/0e44fa40-f40f-49b4-9208-b264ca22665b" />

