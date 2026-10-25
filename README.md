# Python-Basics-25BCON2088
# Student Information System in Python

## 📌 Overview

This project demonstrates the use of **classes and objects in Python** to store and display student information. It defines a `Student` class with attributes for a student's name, roll number, and marks.

## 🎯 Objectives

- Understand object-oriented programming (OOP) in Python.
- Learn how to define a class and create objects.
- Use a constructor to initialize object attributes.
- Display formatted student information.

## 💻 Source Code

```python
class Student:
    def __init__(self, name, roll, marks):
        self.name = name
        self.roll = roll
        self.marks = marks


s1 = Student("Rahul", 101, 87.5)

print("Name:", s1.name)
print("Roll:", s1.roll)
print("Marks: {:.1f}".format(s1.marks))
```

## ⚙️ How It Works

1. **Class Definition:** The `Student` class defines the structure of a student object.
2. **Constructor:** The `__init__()` method initializes the object's attributes.
3. **Object Creation:** The `s1` object is created with the values `"Rahul"`, `101`, and `87.5`.
4. **Attribute Access:** The program accesses the student's details using `s1.name`, `s1.roll`, and `s1.marks`.
5. **Formatted Output:** The `format()` method displays marks to one decimal place.

## 📤 Output

```text
Name: Rahul
Roll: 101
Marks: 87.5
```

## 🛠️ Requirements

- Python 3.x
- Any Python-compatible editor, such as VS Code, PyCharm, or Google Colab.

No external libraries are required.

## ▶️ How to Run

1. Copy the code into a file named `student.py`.
2. Open a terminal in the directory containing the file.
3. Execute the following command:

```bash
python student.py
```

Alternatively, run the code in a Google Colab notebook.

## 📚 Concepts Covered

- Classes and objects
- Constructors (`__init__`)
- Instance attributes
- The `self` parameter
- String formatting
- Basic output operations

## 🚀 Future Improvements

- Accept student details as user input.
- Add validation for roll numbers and marks.
- Support multiple student records.
- Calculate grades based on marks.
- Store student information in a file or database.

## 👨‍💻 Author

Created as a beginner-friendly Python object-oriented programming exercise.

---

⭐ If you find this project useful, consider giving the repository a star.
