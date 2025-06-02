# EX: 6.3 ABSTRACT CLASS METHOD
- **Name:** Naveen P
- **Registration Number:** 212222050039

### AIM: To Create the abstract method calculate_area which is of the abstract class 'Shape'

### ALGORITHM:
Step1:Get input from the user

Step2:put class function to define the function using self

Step3:By using the function to find the area of the rectangle and circle Step4:Execute the program.

### PROGRAM:
```from abc import ABC
class Shape(ABC):
            def calculate_area(self):
                Pass
class Rectangle(Shape):
               length = 5
               breadth =3
               def calculate_area(self):
                   print("Area of a rectangle:",self.length * self.breadth)
class Circle(Shape):
             radius = 4
             def calculate_area(self):
                     print("Area of a circle:",3.14 * self.radius * self.radius)
a=Rectangle()
b=Circle()
a.calculate_area()
b.calculate_area()
```
### OUTPUT:
![image](https://github.com/user-attachments/assets/a4c70e22-b3e0-417a-86d7-41f547c9d60d)


### RESULT: Thus, the program has been successfully executed.
