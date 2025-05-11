# 🐍 Python-Learning

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/notfawadmir/Python-Learning/pulls)
[![Stars](https://img.shields.io/github/stars/notfawadmir/Python-Learning?style=social)](https://github.com/notfawadmir/Python-Learning/stargazers)

> 📚 A comprehensive collection of Python resources designed to take you from beginner to proficient Python developer.

## 📋 Table of Contents
- [Introduction](#introduction)
- [Technologies & Tools](#technologies--tools)
- [Learning Path](#learning-path)
- [Topics Covered](#topics-covered)
- [Installation & Setup](#installation--setup)
- [Usage Examples](#usage-examples)
- [Contributing](#contributing)
- [Learning Resources](#learning-resources)
- [License](#license)
- [Contact](#contact)

## 📖 Introduction

Welcome to the **Python-Learning** repository! This carefully curated collection of Python scripts, exercises, and projects is designed to provide a structured learning path for Python programming. Whether you're taking your first steps in coding or looking to expand your Python expertise, this repository offers practical examples and challenges to help you master Python concepts through hands-on practice.

What makes this repository special:
- 🎯 **Focused examples** that demonstrate one concept at a time
- 🔄 **Progressive difficulty** that builds on previous knowledge
- 💻 **Practical applications** showing real-world use cases
- 📝 **Well-documented code** with explanations and best practices
  

## 🔧 Technologies & Tools

This repository leverages:

- **Python 3.8+**: Utilizing modern Python features and syntax
- **Standard Library Modules**:
  - `datetime` - Date and time manipulation
  - `math` - Mathematical functions
  - `os` & `sys` - System interfaces

- **Development Tools**:
  - `Jupyter Notebooks` - For interactive learning experiences
  - `Google Colab` - For smooth workflow

## 🗺️ Learning Path

This repository is organized to follow a logical progression:

1. **Foundations** (01-04): Master the core syntax and basic structures
2. **Essential Tools** (05-06): Learn to work with modules and files
3. **Object-Oriented Principles** (07): Understand classes and inheritance
4. **Professional Practices** (08-10): Explore error handling and Pythonic patterns
5. **Application** (11): Apply knowledge in mini-projects

## 🧠 Topics Covered

### Beginner Level
- **Variables and Data Types**: Integers, floats, strings, booleans
- **Basic Operations**: Arithmetic, assignment, comparison
- **String Manipulation**: Formatting, methods, slicing
- **Lists and Dictionaries**: Creating, accessing, modifying
- **Control Flow**: `if`/`else` statements, `for`/`while` loops
- **Basic Functions**: Defining, parameters, return values

### Intermediate Level
- **Advanced Data Structures**: Sets, tuples, named tuples
- **List/Dict Comprehensions**: Elegant data transformations
- **Function Advanced Features**: Arguments packing/unpacking, decorators
- **File I/O**: Reading/writing text and binary files
- **Modules and Packages**: Importing, creating, namespace management
- **Object-Oriented Programming**: Classes, inheritance, encapsulation, polymorphism

### Advanced Level
- **Functional Programming**: Lambda functions, map/filter/reduce
- **Generators and Iterators**: Efficient sequence processing
- **Context Managers**: Resource management with `with` statements
- **Concurrency**: Threading, multiprocessing, async programming basics
- **Meta-programming**: Reflection, dynamic attributes, descriptors
- **Performance Optimization**: Profiling and improving code efficiency

## 💻 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/notfawadmir/Python-Learning.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Python-Learning
   ```

3. **Set up a virtual environment** (recommended):
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

4. **Install dependencies** (if any):
   ```bash
   pip install -r requirements.txt
   ```

5. **Run scripts directly**:
   ```bash
   python 01-basics/variables.py
   ```

6. **Or launch Jupyter Notebook** (for interactive examples):
   ```bash
   pip install jupyter
   jupyter notebook
   ```

## 🎮 Usage Examples

### Example 1: Basic Variable Operations
```python
# From Session NO. 1/
name = "Python Learner"
age = 25
is_programmer = True

print(f"Hello, {name}!")
print(f"In five years, you'll be {age + 5} years old.")
print(f"Programmer status: {is_programmer}")

# Output:
# Hello, Python Learner!
# In five years, you'll be 30 years old.
# Programmer status: True
```

### Example 2: List Comprehension
```python
# From Session NO. 10/list_comprehensions.py
numbers = range(10)

# Traditional approach
squares_traditional = []
for num in numbers:
    squares_traditional.append(num ** 2)

# Pythonic approach
squares_pythonic = [num ** 2 for num in numbers]

print("Traditional:", squares_traditional)
print("Pythonic:", squares_pythonic)

# Output:
# Traditional: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
# Pythonic: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
```

### Example 3: Simple OOP
```python
# From Session NO.13/basic_class.py
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def greet(self):
        return f"Hello, my name is {self.name} and I'm {self.age} years old."
    
    def celebrate_birthday(self):
        self.age += 1
        return f"Happy birthday! Now I'm {self.age} years old."

# Creating an instance
python_student = Person("Alex", 28)
print(python_student.greet())
print(python_student.celebrate_birthday())

# Output:
# Hello, my name is Alex and I'm 28 years old.
# Happy birthday! Now I'm 29 years old.
```

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make to enhance this learning resource are **greatly appreciated**.

1. **Fork the repository**
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/amazing-improvement
   ```
3. **Make your changes** (Add or improve examples, fix bugs, etc.)
4. **Commit your changes**:
   ```bash
   git commit -m 'Add some amazing improvement'
   ```
5. **Push to your branch**:
   ```bash
   git push origin feature/amazing-improvement
   ```
6. **Open a pull request**

You can also contribute by:
- **Opening issues** for bugs or suggested improvements
- **Improving documentation**
- **Sharing the repository** with fellow Python learners

## 📚 Learning Resources

Beyond this repository, here are some excellent resources to further your Python journey:

- **Books**:
  - "Python Crash Course" by Eric Matthes
  - "Fluent Python" by Luciano Ramalho
  - "Automate the Boring Stuff with Python" by Al Sweigart

- **Online Courses**:
  - [Official Python Tutorial](https://docs.python.org/3/tutorial/)
  - [Real Python](https://realpython.com/)
  - [PyBites](https://pybit.es/)

- **Practice Platforms**:
  - [LeetCode](https://leetcode.com/)
  - [HackerRank](https://www.hackerrank.com/)
  - [Exercism](https://exercism.io/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

For questions, feedback, or collaboration, feel free to reach out:

- **GitHub**: [notfawadmir](https://github.com/notfawadmir)
- **Email**: notfawadmir@gmail.com
- **LinkedIn**: [Connect on LinkedIn](https://www.linkedin.com/in/fawad-ahmed-mir-9621762ba)

---

⭐ **Star this repository** if you find it helpful! ⭐

Happy coding and enjoy your Python learning journey! 🐍
