# Exp.No:28  
## Abstraction

### AIM  

To write a Python program to create the abstract method  calculate_area  which is  of the abstract class 'Shape'. The implementation of this abstract class can be defined in the sub-classes that inherit the class 'Shape'.  'Rectangle' and 'Circle' are the two sub-classes that inherit the abstract class 'Shape'.

### ALGORITHM

1. Start the Program.
2. Import ABC (Abstract Base Class) to define an abstract class.
3. Define an abstract class Shape with an abstract method calculate_area().
4. Create subclass Rectangle:
   Set length = 5 and breadth = 3.
   Implement calculate_area() to return length × breadth.
5. Create subclass Circle:
   Set radius = 4.
   Implement calculate_area() to return π × radius² (π ≈ 3.14).
6. Create objects rec and cir for Rectangle and Circle.
7. Call calculate_area() for each object.
8. Print the areas of the rectangle and the circle.
9. End the Program.

### PROGRAM

```
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
print("Area of a rectangle:", rec.calculate_area()) 
print("Area of a circle:", cir.calculate_area()) 
```

### OUTPUT

![image](https://github.com/user-attachments/assets/95485111-3a85-4547-84a9-168c30664578)

### RESULT

Thus the python program for calculating area using abstract method was successfully created.
