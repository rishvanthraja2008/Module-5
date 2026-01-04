# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
```
class employee:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def display(self):
        if self.a>500000:
            print(f"({self.a}, '{self.b}')  Valid Employee")
        else:
            print(f"({self.a}, '{self.b}')  Invalid Employee")
    

a=int(input())
b=input()
obj=employee(a,b)
obj.display()
```
## Sample Output
<img width="930" height="248" alt="image" src="https://github.com/user-attachments/assets/9eedbfd2-a0be-4940-8de8-b3f858d660e1" />

