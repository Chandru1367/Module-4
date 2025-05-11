# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `umbrella` and a method `rain` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `umbrella`.
3. **Define the method**: Inside the class, define the method `rain` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class umbrella:
    def rain(self, radius):
        area = math.pi * radius ** 2
        return area
radius = float(input())
obj = umbrella()
area = obj.rain(radius)
print(f"Area of circle: {area:.2f}")
```

## Output
![image](https://github.com/user-attachments/assets/b922cee8-3d41-4c02-ad61-6fc4ed5e99ac)


## Result
Thus the program executed successfully.
