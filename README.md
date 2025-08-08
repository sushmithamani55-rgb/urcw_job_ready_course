# URCW Job Ready Course Setup Instructions

# Ensure you have Python and Git installed on your system.
# For Windows users, you can use the following commands to set up your environment.
# Windows Setup Instructions
# Open a terminal or command prompt and follow these steps to set up your environment:
cd c:/Users/<your_administrator_id>/
# Create a directory for your projects
mkdir PycharmProjects
# Navigate to the projects directory
cd PycharmProjects
# Check if Git is installed
git --version
# If Git is not installed, download and install it from https://git-scm.com/downloads
# After installing Git, you can clone the repository
git clone https://github.com/alagappainfotech/urcw_job_ready_course.git
# Navigate into the cloned repository
cd urcw_job_ready_course

git checkout main
# If the folder already exists, you can update it with:
git pull origin main

# Check if Python is installed
python --version
# If Python is not installed, download and install it from https://www.python.org/downloads/
# After installing Python, you can check if pip is installed
pip --version
# If pip is not installed, you can install it by following the instructions at https://pip.pypa.io/en/stable/installation/
# Check if pip3 is installed
pip3 --version
python3 --version

# Create a Python virtual environment
# If you are using Python 3, you can create a virtual environment with:
python -m venv venv
# Activate the virtual environment
source venv/Scripts/activate
# Check if the virtual environment is activated
# You should see the virtual environment name in your terminal prompt, like (venv) C:\Users\<your_administrator_id>\PycharmProjects\urcw_job_ready_course>

# Install the required dependencies
pip install -r requirements.txt


# URCW Job Ready Course

Welcome to the **URCW Job Ready Course** repository! This course is designed to help you master Python programming and related job-ready skills. Please follow the instructions below to set up your environment, contribute your work, and learn effectively.

---

## Table of Contents

- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Course Curriculum](#course-curriculum)
- [How to Submit Your Work](#how-to-submit-your-work)
- [Adding New Lessons](#adding-new-lessons)
- [Python Concepts Covered](#python-concepts-covered)
- [Contributing Guidelines](#contributing-guidelines)
- [Contact](#contact)

---

## Getting Started

1. **Clone the Repository**
    ```sh
    git clone https://github.com/alagappainfotech/urcw_job_ready_course.git
    cd urcw_job_ready_course
    ```

2. **Set Up Python Virtual Environment**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    # or
    source venv/Scripts/activate  # On Windows
    ```

3. **Install Dependencies**
    ```sh
    pip install -r requirements.txt
    ```

---

## Repository Structure

```
urcw_job_ready_course/
├── basics/                    # Core Python lessons
│   ├── 1/                    # Primitive data types and operators
│   ├── 2/                    # Variables and collections
│   ├── 3/                    # Control flow and iterables
│   ├── 4/                    # Functions
│   ├── 5/                    # Modules
│   ├── 6/                    # Classes and OOP
│   ├── 7/                    # Advanced topics
│   ├── 8/                    # String manipulation and formatting
│   ├── 9/                    # File handling and I/O
│   └── 10/                   # Regular expressions
├── django/                    # Django web framework lessons
│   ├── 1_Introduction_to_Django.py
│   └── 2_Django_Models_and_Database.py
├── flask/                     # Flask web framework lessons
│   └── 1_Introduction_to_Flask.py
├── exercises/                 # Practice exercises
│   ├── exercise_01.py        # Basic exercises
│   ├── exercise_02.py
│   ├── exercise_03.py
│   ├── exercise_04.py
│   ├── exercise_05.py
│   ├── exercise_08_string_manipulation.py
│   ├── exercise_09_file_handling.py
│   ├── exercise_10_regex.py
│   ├── exercise_django_01.py
│   └── exercise_flask_01.py
├── python_outputs/           # Student submissions
├── main.py                   # Main application
├── requirements.txt          # Python dependencies
└── README.md                # This file
```

---

## Course Curriculum

### Core Python Programming (Lessons 1-10)

**Lesson 1: Primitive Data Types and Operators**
- Numbers, strings, booleans
- Mathematical operators
- Comparison operators
- Logical operators

**Lesson 2: Variables and Collections**
- Lists, tuples, dictionaries, sets
- Collection operations and methods
- List comprehensions

**Lesson 3: Control Flow and Iterables**
- Conditional statements (if/elif/else)
- Loops (for, while)
- Exception handling
- File I/O operations

**Lesson 4: Functions**
- Function definition and calling
- Arguments and parameters
- Lambda functions
- Decorators and closures

**Lesson 5: Modules**
- Import statements
- Creating modules
- Package management

**Lesson 6: Classes and Object-Oriented Programming**
- Class definition and instantiation
- Inheritance and polymorphism
- Encapsulation
- Special methods

**Lesson 7: Advanced Topics**
- Generators and iterators
- Context managers
- Decorators
- Metaclasses

**Lesson 8: String Manipulation and Formatting**
- String methods and operations
- String formatting (f-strings, .format())
- Regular expressions basics
- Text processing

**Lesson 9: File Handling and I/O Operations**
- File reading and writing
- CSV and JSON processing
- Binary file operations
- Error handling in file operations

**Lesson 10: Regular Expressions**
- Pattern matching
- String validation
- Text extraction and replacement
- Advanced regex features

### Web Development with Django

**Django Lesson 1: Introduction**
- Django philosophy and features
- Project setup and structure
- Basic views and URL routing
- Templates and Jinja2
- Forms and validation
- Admin interface

**Django Lesson 2: Models and Database**
- Django ORM
- Model relationships
- Database migrations
- Query operations
- Model methods and properties

### Web Development with Flask

**Flask Lesson 1: Introduction**
- Flask philosophy and features
- Application setup
- Routes and views
- Templates and Jinja2
- Forms and request handling
- API development

---

## Python Concepts Covered

### Core Concepts
- ✅ Variables and Data Types
- ✅ Input/Output Operations
- ✅ Operators and Expressions
- ✅ Conditional Statements
- ✅ Loops and Iteration
- ✅ Functions and Scope
- ✅ Lists, Tuples, Sets, Dictionaries
- ✅ String Manipulation
- ✅ Exception Handling
- ✅ File I/O Operations
- ✅ Modules and Packages
- ✅ List Comprehensions
- ✅ Lambda Functions
- ✅ Classes and Objects
- ✅ Inheritance and Polymorphism
- ✅ Generators and Iterators
- ✅ Decorators
- ✅ Regular Expressions
- ✅ Context Managers

### Web Development
- ✅ Django Framework
- ✅ Flask Framework
- ✅ Database Operations
- ✅ API Development
- ✅ User Authentication
- ✅ Form Handling
- ✅ Template Systems

---

## How to Submit Your Work

1. **Create Your Directory under python_outputs folder**  
   Format: `yourname_class_year_python`  
   Example: `john_csc_1_python`

2. **Add Your Files**  
   Place your solutions, scripts, and outputs in your directory.

3. **Commit and Push**
    ```sh
    git add yourname_class_year_python/
    git commit -m "Add solutions for lesson X"
    git push origin main
    ```

---

## Adding New Lessons

To help students learn missing Python concepts, add new lessons in the appropriate folder. Each lesson should:

- Be a separate `.py` file with detailed comments
- Include example code and exercises
- Follow the established naming convention
- Include practical examples and use cases

**Example Lesson Structure:**
```python
####################################################
## Lesson Title
####################################################

# Introduction and overview
# Detailed explanations with examples
# Practical applications
# Exercises for students
```

---

## Exercises and Practice

Each lesson includes comprehensive exercises:

- **Basic Exercises**: Fundamental concept practice
- **Intermediate Exercises**: Real-world applications
- **Advanced Exercises**: Complex problem-solving
- **Project-Based Exercises**: Complete application development

### Exercise Categories:
- String manipulation and text processing
- File handling and data processing
- Regular expressions and pattern matching
- Web development with Django and Flask
- API development and testing
- Database operations and ORM usage

---

## Contributing Guidelines

- Always pull the latest changes before pushing
- Write clear, commented code
- Submit your work in your individual directory
- For new lessons, follow the commenting style shown above
- Test your code before submitting
- Include proper error handling
- Follow PEP 8 coding standards

---

## Contact

For questions or support, please open an issue or contact the course instructor.

---

## Additional Resources

### Online Courses
- **Udacity - Version Control with Git**
  - Link: https://www.udacity.com/course/version-control-with-git--ud123
  - Topics: Version control fundamentals, Git commands, branching and merging
  - Cost: Free

- **MIT OpenCourseWare - 6.0001 Introduction to Computer Science and Programming in Python**
  - Link: https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/
  - Topics: Core computer science concepts using Python
  - Cost: Free

### Recommended Learning Path
1. Complete all core Python lessons (1-10)
2. Practice with exercises for each lesson
3. Build small projects using learned concepts
4. Learn Django for full-stack web development
5. Learn Flask for lightweight web applications
6. Practice with real-world projects
7. Contribute to open-source projects

---

## Best Practices

1. **Code Organization**
   - Use meaningful variable and function names
   - Write clear comments and documentation
   - Follow PEP 8 style guidelines
   - Use proper indentation and spacing

2. **Error Handling**
   - Always handle potential exceptions
   - Provide meaningful error messages
   - Use try-except blocks appropriately
   - Validate user input

3. **Testing**
   - Write tests for your functions
   - Test edge cases and error conditions
   - Use unit testing frameworks
   - Practice test-driven development

4. **Version Control**
   - Commit frequently with meaningful messages
   - Use descriptive branch names
   - Review code before merging
   - Keep commits atomic and focused

5. **Documentation**
   - Write clear docstrings for functions
   - Document complex algorithms
   - Include usage examples
   - Keep README files updated