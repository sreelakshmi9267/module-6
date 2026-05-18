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
    __length = 0
    __breadth = 0
    def __init__(self,length,breadth):
        self.__length = 5
        self.__breadth = 3
    def show(self):
        print(self.__length)
        print(self.__breadth)
            
rect = Rectangle(5,3)
rect.show()
```
## Output
<img width="537" height="204" alt="Screenshot 2026-05-18 191733" src="https://github.com/user-attachments/assets/6194c934-1dda-4bad-b32e-709c4f40d6aa" />

## Result
Thus,defining a class Rectangle with private member variables __length and __breadth is executed successfully.

