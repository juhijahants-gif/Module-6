# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an *abstract class* named Shape with an *abstract method* calculate_area, and implement this method in two subclasses: Rectangle and Circle.

---

## 🧠 ALGORITHM
```
1. *Import ABC module*:
   - Use from abc import ABC, abstractmethod to define abstract classes and methods.

2. **Create Abstract Class Shape**:
   - Define an abstract method calculate_area() with @abstractmethod.

3. **Create Subclass Rectangle**:
   - Set default values for length and breadth.
   - Override calculate_area() to compute the rectangle area.

4. **Create Subclass Circle**:
   - Set default value for radius.
   - Override calculate_area() to compute the circle area.

5. *Create Objects & Call Methods*:
   - Instantiate Rectangle and Circle.
   - Call their calculate_area() methods.

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
      return 3.14 * self.radius * self.radius
rec=Rectangle()
rec.calculate_area()
cir=Circle()
cir.calculate_area()
print("Area of a rectangle:", rec.calculate_area()) #call to 'calculate_area' method defined inside the class 'Rectangle'
print("Area of a circle:", cir.calculate_area()) #call to 'calculate_area' method defined inside the class 'Circle'.
```
## Output
![WhatsApp Image 2025-10-19 at 20 18 56_6e030460](https://github.com/user-attachments/assets/9262ae2c-0a8e-41f4-92d5-f4048258e7ad)


## Result
The program successfully calculates area of shapes using abstarct method and classes
