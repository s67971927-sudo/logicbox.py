Interactive Data Collector

A simple Python program that collects basic personal information from the user and displays the entered data along with its data type and memory address.

📌 Description

The Interactive Data Collector is a beginner-friendly Python project designed to demonstrate:

User input using input()

Converting input into different data types

Python's built-in type() function

Python's built-in id() function

Basic output formatting using print()

The program asks the user for their:

Name

Age

Height in meters

Favorite number

It then displays the collected information, its data type, and its memory address.

🛠️ Requirements

You only need:

Python 3.x

No external libraries or packages are required.

🚀 How to Run

Make sure Python 3 is installed on your computer.

Save the program in a file, for example:

data_collector.py


Open a terminal or command prompt.

Navigate to the folder containing the file.

Run the program:

python data_collector.py


On some systems, you may need:

python3 data_collector.py

💻 Example
Welcome to the Interactive Data Collector!

Please Enter your name: Alex
Please Enter your age: 20
Please enter your height in meters: 1.75
Please enter your favorite number: 7

Thank you! Here is the information we collected:

Name: Alex (Type is: <class 'str'> Memory Address: 123456789 )
Age: 20 (Type is: <class 'int'> Memory Address: 123456790 )
Height: 1.75 (Type is: <class 'float'> Memory Address: 123456791 )
Favorite Number: 7 (Type is: <class 'int'> Memory Address: 123456792 )

thank you for using the personal data collector.good bye!

https://drive.google.com/file/d/1Jpj2BLxAwUlNTYrmP_2suiHzOr0fs0P4/view?usp=sharing

 
Note: The memory addresses shown by id() will be different each time the program runs and may differ between Python implementations.

📚 Concepts Demonstrated
input()

The input() function is used to receive information from the user.

a = input("Please Enter your name: ")


By default, input() returns the user's input as a string.

Type Conversion

The program converts user input into different types:

b = int(input("Please Enter your age: "))
c = float(input("Please enter your height in meters: "))
e = int(input("Please enter your favorite number: "))


int() converts a value to an integer.

float() converts a value to a floating-point number.

str is used for text such as the user's name.

type()

The type() function shows the data type of a variable.

Example:

type(a)


Possible output:

<class 'str'>

id()

The id() function returns an integer that identifies an object during its lifetime.

Example:

id(a)


The returned value is implementation-dependent and can change between program runs.

⚠️ Input Requirements

The program expects:

Name: Text

Age: A whole number, such as 18

Height: A decimal number in meters, such as 1.75

Favorite number: A whole number, such as 7

Entering invalid input, such as letters when an integer is expected, will cause a ValueError.

🎯 Learning Objectives

This project is useful for beginners learning Python because it demonstrates:

Variables

User input

Data types

Type conversion

Functions

print()

type()

id()

Basic program structure

📁 Project Structure
Interactive-Data-Collector/
│
├── data_collector.py
└── README.md

🔮 Possible Improvements

Future versions could include:

Input validation

Error handling with try and except

More information fields

Better formatted output

Saving the collected information to a file

Calculating BMI from height and weight

Allowing the user to collect information multiple times
