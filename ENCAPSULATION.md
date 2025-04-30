# Exp.No:29  
## Encapsulation

### AIM  

To write a Python program to create a class Employee with public method show to display the details of the employee.

### ALGORITHM

1. Start the Program.
2. Define a class Employee with a constructor __init__:
3. Initialize public data members name and salary.
4. Create an object emp of the Employee class with given name and salary.
5. Access and print the public data members name and salary.
6. Print again the name and salary.
7. End the program.

### PROGRAM

```

class Employee:
    # constructor
    def __init__(self, name, salary):
        # public data members
        self.name = name
        self.salary = salary

    # public instance methods
    
# creating object of a class
emp = Employee('Jessa', 10000)

# accessing public data members
print("Name: ", emp.name, 'Salary:', emp.salary)

# call public method of the class
print("Name: ", emp.name, 'Salary:', emp.salary)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/ebc32dbc-a057-4d54-8d82-a656ef2c0e08)

### RESULT

Thus the Python program to create a class Employee with public method show to display the details of the employee was successfully created.
