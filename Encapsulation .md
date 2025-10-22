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
    def __init__(self, length, width):
        self.__length = length  
        self.__width = width    
rect = Rectangle(5, 3)
rect.print_values()
## Output
<img width="1271" height="306" alt="Screenshot 2025-10-22 212255" src="https://github.com/user-attachments/assets/c645376c-f7e4-4988-945d-6eabb727131a" />

## Result
Thus the program runs successfully.
