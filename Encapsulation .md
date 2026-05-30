# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length      # private variable
        self.__breadth = breadth   # private variable

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)

# Creating object
r1 = Rectangle(10, 5)

# Accessing values using method
r1.display()
```
## Output
<img width="157" height="46" alt="image" src="https://github.com/user-attachments/assets/959f8ba2-9400-4105-8e2b-d54f48a19c7b" />

## Result
Thus, the program to demonstrate Encapsulation using private variables in Python is successfully executed.

