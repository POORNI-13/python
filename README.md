TASK 1

>>>from math import pi
>>> radius = float(input ("Input the radius of the circle : "))
Input the radius of the circle : 10
>>> print ("The area of the circle with radius " + str(radius) + " is: " + str(pi * radius**2))
The area of the circle with radius 10.0 is: 314.1592653589793

TASK 2

>>> filename = input("Input the Filename: ")
Input the Filename: pqr.py
>>> f_extns = filename.split(".")
>>> print ("The extension of the file is : " + repr(f_extns[-1]))
The extension of the file is : 'py'
