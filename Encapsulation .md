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
from abc import ABC
class Shape(ABC):
    def calculate_area(self):
        pass
class Rectangle(Shape):
    length = 5
    breadth =3 
    def calculate_area(self):
        return self.length * self.breadth

class Circle(Shape):
  radius = 4
  def calculate_area(self):
        return self.radius * self.radius*3.14

rec=Rectangle()
cir=Circle()#object created for the class 'Rectangle'
#object created for the class 'Circle'
print("Area of a rectangle:", rec.calculate_area()) #call to 'calculate_area' method defined inside the class 'Rectangle'
print("Area of a circle:", cir.calculate_area()) #call to 'calculate_area' method defined inside the class 'Circle'.
## Output
<img width="1274" height="297" alt="Screenshot 2025-10-22 211928" src="https://github.com/user-attachments/assets/17b7ca08-3e3c-4398-8e09-5d39ce5f62c7" />


## Result
Thus the program runs successfully.
