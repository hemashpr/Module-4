# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```python
import math

class CSE:
    def mech(self, r):
        print("Area of circle:", round(math.pi * r**2, 2))


r = int(input())

a = CSE()
a.mech(r)
```

## Output
<img width="611" height="183" alt="image" src="https://github.com/user-attachments/assets/fdf90120-fdc7-41d7-bbb9-aa3d2d6f26bf" />



## Result
Thus , the program has been executed succesfully.
