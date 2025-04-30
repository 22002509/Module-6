# Exp.No:27  
## Operator Overloading

---

### AIM  
To write a Python program that performs the division of two complex numbers using binary + operator overloading with a class named complex.

---

### ALGORITHM

1.	Start the program.
2.	Define a class named complex to represent a complex number.
3.	Inside the class, define the __init__() method to initialize the real and imaginary parts.
4.	Define the __add__() method to overload the binary + operator.
5.	In the __add__() method, perform:
   •	Real part of result = real part of first object ÷ real part of second object.
   •	Imaginary part of result = imaginary part of first object ÷ imaginary part of second object.
6.	Return the result as a tuple.
7.	Create two objects (Ob1, Ob2) of the complex class with values.
8.	Use the + operator between the two objects to trigger the overloaded __add__() method.
9.	Display the result.
10. End the program.


---

### PROGRAM

```
#RegNo:212222040120
#Name:PRASANNA R
class complex:
    def __init__(self, real, imag):
        self.real = real
        self.imag = imag

    def __add__(self, other):
        real_part = self.real / other.real
        imag_part = self.imag / other.imag
        return (real_part, imag_part)

Ob1 = complex(10, 21)
Ob2 = complex(2, 3)

result = Ob1 + Ob2
print(result)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/51965e8a-f59c-4a8d-9ed8-6833e5b8f6a0)


### RESULT
This program demonstrates operator overloading using the + operator to perform division of the real and imaginary parts of two complex numbers.
