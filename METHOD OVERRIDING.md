# Exp.No:26  
## Method Overriding

---

### AIM  
To write a Python program to demonstrate method overriding by creating a parent class Fish with a method type, and a child class Shark that overrides the type method.

### ALGORITHM

1.	Start the program.
2.	Define a class named Fish.
3.	Inside the Fish class, define a method type that prints "fish".
4.	Define a child class named Shark that inherits from the Fish class.
5.	Override the type method in the Shark class to print "shark".
6.	Create an object of the Fish class and call the type method.
7.	Create an object of the Shark class and call the type method.
8.	End the program.


### PROGRAM

```
#Reg.No:212222040120
#Name:PRASANNA R
class Fish:
    def type(self):
        print("fish")

class Shark(Fish):
    def type(self):
        print("shark")

f = Fish()
f.type()

s = Shark()
s.type()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/169c1d23-555b-4fb3-be18-c1bd4b9f78b8)


### RESULT
Thus, the Python program to demonstrate method overriding using a parent class Fish and a child class Shark has been implemented and executed successfully.








