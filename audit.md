# PYTHON CODE AUDIT REPORT
## Project: Student Information System Using Classes and Objects

### 1. Project Information

- **Project Name:** Student Information System
- **Programming Language:** Python 3
- **Program Type:** Object-Oriented Programming (OOP)
- **Audit Type:** Code Quality and Functional Audit
- **Purpose:** To create a student object and display the student's name, roll number, and marks.

### 2. Source Code

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

**Note:** The original code uses `init` instead of `__init__`. The code above corrects this issue so that the program executes successfully.

### 3. Audit Objectives

The audit aims to verify:

1. Correct use of Python classes and objects.
2. Proper initialization of student attributes.
3. Correct display of student information.
4. Accuracy of the program's output.
5. Code readability and efficiency.

### 4. Code Review and Audit Findings

| Audit Parameter | Observation | Status |
|---|---|---|
| Syntax | Correct in the revised code | PASS |
| Class Definition | `Student` class is properly defined | PASS |
| Constructor | `__init__()` initializes attributes | PASS |
| Object Creation | Student object is created correctly | PASS |
| Attribute Access | Attributes are accessed correctly | PASS |
| Output Formatting | Marks display to one decimal place | PASS |
| Input Validation | No validation is implemented | IMPROVEMENT NEEDED |
| External Dependencies | No external libraries required | PASS |

### 5. Program Logic

1. Define the `Student` class.
2. Create a constructor using `__init__()`.
3. Initialize the student's name, roll number, and marks.
4. Create an object named `s1`.
5. Assign the values `"Rahul"`, `101`, and `87.5`.
6. Display the student's information using `print()`.

### 6. Test Case Analysis

| Test Case | Expected Result | Status |
|---|---|---|
| Create student
