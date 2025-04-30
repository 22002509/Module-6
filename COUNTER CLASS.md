# Exp.No:30  
## COUNTER CLASS

### AIM  

To write a Python program to Define the abstract base class named Polygon and also define the abstract method. This base class inherited by the various subclasses. Implement the abstract method in each subclass.
Create the object of the subclasses and invoke the sides() method.

### ALGORITHM

1. Start the Program.
2. Import ABC to create an abstract base class.
3. Define an abstract class Polygon with an abstract method sides().
4. Create subclasses Triangle, Pentagon, Hexagon, and Square:
   Each subclass implements the sides() method to print the number of sides.
5. Create objects of Triangle, Square, Pentagon, and Hexagon.
6. Call the sides() method for each object to display their sides.
7. End the program.

### PROGRAM

```

from abc import ABC  
  
class Polygon(ABC):   
  
   # abstract method   
   def sides(self):   
      pass  
  
class Triangle(Polygon):   
  
     
   def sides(self):   
      print("Triangle has 3 sides")   
  
class Pentagon(Polygon):   
   def sides(self):
       print("Pentagon has 5 sides")
   #Add code here
class Hexagon(Polygon):   
   def sides(self):
       print("Hexagon has 6 sides")
   #Add your code
class square(Polygon):   
  
   def sides(self):   
      print("I have 4 sides")   
  
# Driver code   
t = Triangle()   
t.sides()  
  
s = square()   
s.sides()
  
p = Pentagon()   
p.sides()
  
k = Hexagon()   
k.sides()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/74d90fd7-70aa-4d1d-ac81-52660a4cbca0)

### RESULT

Thus the python program for sides using abstract method was successfully created.
