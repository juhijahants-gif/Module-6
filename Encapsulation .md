# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement *Encapsulation* in Python by defining a class Rectangle with *private member variables* __length and __breadth.

---

## 🧠 ALGORITHM

1. *Define the Class*:
   - Create a class Rectangle with two private attributes: __length and __breadth.

2. *Initialize Variables*:
   - Use the __init__() constructor to set initial values for __length and __breadth.

3. *Print Values*:
   - Display the private variables from within the class to demonstrate access.

4. *Instantiate the Object*:
   - Create an object of the Rectangle class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length      
        self.__breadth = breadth    
    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)
rect = Rectangle(10, 5)
rect.display()
```
## Output
<img width="310" height="84" alt="image" src="https://github.com/user-attachments/assets/df418e57-b375-4bdf-8f11-2e0def3c72ec" />


## Result
The program successfully demonstrates Encapsulation in Python by defining a class with private data members (__length and __breadth).
The private variables are accessed only through class methods, ensuring data protection and controlled access.
