# Python Programming Course

## Lecture 1: Introduction to Python

### What is Python?
1. Python is a free and open-source programming language.
2. It was developed in the early 1990s by a Dutch programmer, Guido Van Rossum, who worked at Google from 2005 to 2012.
3. The name "Python" was inspired by the British comedy group "Monty Python."
4. It is pronounced as "Pay-thon."

### Why Python?
1. Large companies like Google, YouTube, and Yahoo! constantly require Python developers.
2. Python can be used for desktop applications, games, mobile applications, web development, and networking.
3. Python code is simple, easy to read, and does not need compilation.
4. Python is cross-platform and can run on Linux, Windows, Mac OS X, MS-DOS, iOS, and Android.

### Python Versions
1. There are two main versions: Python 2 and Python 3.
2. Python 3 is more powerful and has fewer errors compared to Python 2.
3. Code written in Python 2 is not compatible with Python 3 and vice versa.

### Installing Python
1. Visit [python.org](http://www.python.org) and download the latest version.
2. Install the downloaded file by following the setup instructions.
3. Know the installation directory in case troubleshooting is needed.



## Preparation Checklist

### 1. Google Account

Ensure you have an active Google account to access Google Colab. If you
don’t have one, [create a Google
account](https://accounts.google.com/signup).

### 2. Install Required Software (Optional)

While Google Colab eliminates the need for local installations, ensure
your local machine has: - A modern browser (e.g., Chrome, Firefox, or
Edge). - Stable internet connection.

### 3. Access the Tutorial Notebook

Download the tutorial notebook provided for this session: - **File
Name**: `Introduction_to_Python.ipynb` - [Download the
file](https://github.com/BMGLab/ComThinkDataSci/blob/main/Introduction_to_Python.ipynb).


For the other practices, please fetch the files:

`Variables_and_Data_Types.ipynb` - [Download the
file](https://github.com/BMGLab/ComThinkDataSci/blob/main/Variables_and_Data_Types.ipynb)


`Operators_and_Expressions.ipynb` - [Download the
file](https://github.com/BMGLab/ComThinkDataSci/blob/main/Operators_and_Expressions.ipynb)


`Data_Structures.ipynb` - [Download the
file](https://github.com/BMGLab/ComThinkDataSci/blob/main/Data_Structures.ipynb)


`Control_Structures.ipynb` - [Download the
file](https://github.com/BMGLab/ComThinkDataSci/blob/main/Control_Structures.ipynb)


`Functions_and_Modules.ipynb` - [Download the
file](https://github.com/BMGLab/ComThinkDataSci/blob/main/Functions_and_Modules.ipynb)



---

## Lecture 2: Python Basics

### Python Files Location
- On Windows, Python is usually installed in:
  - `C:\Users\YourUsername\AppData\Local\Programs\Python`

### Code Editors and IDEs
- IDE (Integrated Development Environment) is a software for writing, editing, and debugging code efficiently.
- Popular Python Editors:
  1. **Python IDLE** (Basic editor, included with Python installation)
  2. **Wing IDE** ([Download here](https://wingware.com/downloads/wingide-101))
  3. **Canopy** ([Download here](https://store.enthought.com/downloads/#default))
  4. **PyCharm** ([Download here](https://www.jetbrains.com/pycharm/download/#section=windows))
  5. **Other editors**: Sublime Text, Visual Studio, Jupyter Notebook, Spyder, Atom

### Programming Concepts
1. **Compilers** convert source code into machine code.
2. **Interpreters** execute code line by line (Python is interpreted).
3. **Debuggers** help find and fix errors.

### Variables and Constants
- A variable stores data that can change.
- Constants store values that do not change.
- Example:
  ```python
  city = "New York"
  print(city)  # Output: New York
  ```

### Variable Naming Rules
1. Cannot start with a number.
2. Cannot contain special characters except `_` (underscore).
3. No spaces allowed in variable names.
4. Reserved keywords (e.g., `True`, `and`, `class`) cannot be used.

---

## Lecture 3: Data Types and Operators

### Data Types in Python
1. **String (`str`)** - Text data, written within quotes.
2. **Integer (`int`)** - Whole numbers.
3. **Float (`float`)** - Decimal numbers.
4. **Boolean (`bool`)** - True or False values.

### Type Conversion
- Convert between different data types:
  ```python
  int("10")  # Converts string "10" to integer 10
  float(5)   # Converts integer 5 to float 5.0
  str(20)    # Converts integer 20 to string "20"
  ```

### Print Function
- Used to display output:
  ```python
  print("Hello, World!")
  print(5 + 3)  # Outputs 8
  ```

### Operators in Python
1. **Arithmetic Operators:** `+`, `-`, `*`, `/`, `//`, `%`, `**`
2. **Comparison Operators:** `==`, `!=`, `>`, `<`, `>=`, `<=`
3. **Logical Operators:** `and`, `or`, `not`
4. **Membership Operators:** `in`, `not in`

---

## Lecture 4: Control Flow

### Conditional Statements
- Used to control the execution of code based on conditions.
  ```python
  age = int(input("Enter your age: "))
  if age < 18:
      print("You are a minor.")
  elif age < 65:
      print("You are an adult.")
  else:
      print("You are a senior citizen.")
  ```

### Loops
1. **For Loop**: Iterates over a sequence.
   ```python
   for i in range(1, 6):
       print(i)
   ```
2. **While Loop**: Repeats as long as the condition is true.
   ```python
   x = 1
   while x <= 5:
       print(x)
       x += 1
   ```
3. **Break Statement**: Exits the loop early.
4. **Continue Statement**: Skips the rest of the code inside the loop and moves to the next iteration.

---

## Lecture 5: Data Structures

### Lists
- Ordered, mutable collection of items.
  ```python
  fruits = ["apple", "banana", "cherry"]
  print(fruits[0])  # Output: apple
  ```

### Tuples
- Ordered but immutable collections.
  ```python
  colors = ("red", "green", "blue")
  print(colors[1])  # Output: green
  ```

### Dictionaries
- Store key-value pairs.
  ```python
  person = {"name": "Alice", "age": 25}
  print(person["name"])  # Output: Alice
  ```

---

## Lecture 6: Functions and Modules

### Defining Functions
- Used to organize reusable blocks of code.
  ```python
  def greet(name):
      print("Hello, " + name + "!")

  greet("Alice")  # Output: Hello, Alice!
  ```

### Importing Modules
- Python has built-in modules that provide extra functionality.
  ```python
  import math
  print(math.sqrt(16))  # Output: 4.0
  ```

### Random Module
- Generate random numbers.
  ```python
  import random
  print(random.randint(1, 10))  # Random number between 1 and 10
  ```

---

This concludes our six-class lecture series on Python programming!

