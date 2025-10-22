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
  class Rectangle:
    length = 0 
    breadth = 0
    def __init__(self):
        self.length = 5
        self.breadth = 3
        print(self.length)
        print(self.breadth)

obj = Rectangle()


## Output
<img width="426" height="278" alt="image" src="https://github.com/user-attachments/assets/1119c016-5dee-47e7-b9ea-72fcde5385ec" />

## Result
Thus the program runs successfully.
