# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```
class Fruits:
    def __init__(self, name):
        """
        Constructor: Called when an object is created.
        """
        self.name = name
        print(f"{self.name} created.")

    def __del__(self):
        """
        Destructor: Called when an object is deleted.
        """
        print(f"Destructor called, {self.name} deleted.")

# Example usage:
# 1. Create the instance (Constructor is triggered)
fruit_obj = Fruits("Fruits")

# 2. Explicitly delete the instance (Destructor is triggered)
del fruit_obj
```
## 🧪 Output
<img width="787" height="183" alt="image" src="https://github.com/user-attachments/assets/ae02d794-1864-4af1-8234-33bfa6b1e3d5" />

## Result
The code is Successful
