1. Python Basics

Python is a high-level, interpreted programming language known for its simplicity and readability. Some key features that make it popular among developers include:

- Easy to Learn and Use: Python's syntax is straightforward to understand, making it suitable for beginners.
- Versatility: Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
- Rich Standard Library: Python comes with a vast collection of libraries and modules for various tasks, reducing the need for extensive code.
- Interpreted and Interactive: Python code is executed line by line, allowing for quick testing and debugging in interactive mode.
- Community Support: Python has a large and active community of developers, providing ample resources, documentation, and third-party packages.

Python is particularly effective in various domains, including web development (with frameworks like Django and Flask), data analysis and machine learning (using libraries like NumPy, pandas, and sci-kit-learn), scripting, automation, and scientific computing.

2. Installing Python

To install Python

1. Windows
   - Download the installer from the official Python website.
   - Run the installer and select the option to add Python to the system PATH.
   - Verify the installation by opening a command prompt and typing `python --version`.
   - Set up a virtual environment using `python -m venv <venv_name>`.

2. macOS:
   - Python is pre-installed on macOS. However, you can install a newer version using Homebrew or download from the Python website.
   - Verify the installation by opening a terminal and typing `python3 --version`.
   - Set up a virtual environment using `python3 -m venv <venv_name>`.

3. Linux:
   - Use the package manager (e.g., apt for Ubuntu) to install Python.
   - Verify the installation by opening a terminal and typing `python3 --version`.
   - Set up a virtual environment using `python3 -m venv <venv_name>`.

3. Python Syntax and Semantics:

Python
 Simple Python program printing "Hello, World!" to the console
print("Hello, World!")

4. Data Types and Variables:

Basic data types in Python include:
- Integer: Whole numbers (e.g., `int_var = 10`).
- Float: Decimal numbers (e.g., `float_var = 3.14`).
- String: Sequence of characters (e.g., `str_var = "Hello"`).
- Boolean: Represents True or False (e.g., `bool_var = True`).

Example script:
python
int_var = 10
float_var = 3.14
str_var = "Hello"
bool_var = True

print(int_var, float_var, str_var, bool_var)


5. Control Structures:

Conditional statements and loops are used for flow control:
Python
Example of if-else statement
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is less than or equal to 5")

Example of a for loop
for i in range(5):
    print(i)

6. Functions in Python:

Functions in Python are blocks of reusable code. They improve code modularity and maintainability. Example:
Python
def add(a, b):
    return a + b

result = add(3, 5)
print("Sum:", result)  # Output: Sum: 8


7. Lists and Dictionaries:

Lists are ordered collections of items, while dictionaries are unordered collections of key-value pairs. Example:
Python
List
numbers = [1, 2, 3, 4, 5]

Dictionary
person = {'name': 'John', 'age': 30, 'city': 'New York'}

# Basic operations
print(numbers[0])        # Accessing the first element of the list
print(person['name'])    # Accessing value using key in dictionary

8. Exception Handling:

Exception handling allows for graceful handling of errors:
python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Error: Division by zero")
finally:
    print("This will always execute")

9. Modules and Packages:

Modules are Python files containing functions and variables, while packages are directories of modules. Example:
python
Importing and using the math module
import math

print(math.sqrt(16))  # Output: 4.0

10. File I/O:

To read from and write to files:python
 Reading from a file
with open('file.txt', 'r') as file:
    content = file.read()
    print(content)

Writing to a file
data = ['apple', 'banana', 'orange']
with open('output. txt', 'w') as file:
    for item in data:
        file.write(item + '\n')
