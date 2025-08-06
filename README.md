# urcw_job_ready_course

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
- [How to Submit Your Work](#how-to-submit-your-work)
- [Adding New Lessons](#adding-new-lessons)
- [Python Concepts to Cover](#python-concepts-to-cover)
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

- `basics/`  
  Contains fundamental Python lessons and exercises.
- `advanced/`  
  Advanced Python topics and projects.
- `your_name_class_year_python/`  
  Each student must create a directory in this format to submit their work.
- `README.md`  
  This file.
- `requirements.txt`  
  Python dependencies.

---

## How to Submit Your Work

1. **Create Your Directory**  
   Format: `yourname_class_year_python`  
   Example: `john_10A_2024_python`

2. **Add Your Files**  
   Place your solutions, scripts, and outputs in your directory.

3. **Commit and Push**
    ```sh
    git add yourname_class_year_python/
    git commit -m "Add solutions for basics lesson 1"
    git push origin main
    ```

---

## Adding New Lessons

To help students learn missing Python concepts, add new lessons in the `basics/` folder. Each lesson should:

- Be a separate `.py` file (e.g., `lists.py`, `functions.py`)
- Contain detailed comments explaining each concept and code block
- Include example code and exercises

**Example: `basics/lists.py`**
```python
# Lesson: Python Lists
# Lists are ordered, mutable collections of items.

# Creating a list
fruits = ['apple', 'banana', 'cherry']
print(fruits)  # Output: ['apple', 'banana', 'cherry']

# Accessing elements
print(fruits[0])  # Output: apple

# Adding elements
fruits.append('orange')
print(fruits)  # Output: ['apple', 'banana', 'cherry', 'orange']

# Removing elements
fruits.remove('banana')
print(fruits)  # Output: ['apple', 'cherry', 'orange']

# Iterate through a list
for fruit in fruits:
    print(fruit)
```

---

## Python Concepts to Cover in `basics/`

Ensure the following topics are included with detailed comments and examples:

- Variables and Data Types
- Input/Output
- Operators
- Conditional Statements (`if`, `elif`, `else`)
- Loops (`for`, `while`)
- Functions (with and without arguments, return values)
- Lists, Tuples, Sets, Dictionaries
- String Manipulation
- Exception Handling
- File I/O
- Modules and Packages
- List Comprehensions
- Lambda Functions
- Basic OOP (Classes and Objects)

---

## Contributing Guidelines

- Always pull the latest changes before pushing.
- Write clear, commented code.
- Submit your work in your individual directory.
- For new lessons, follow the commenting style shown above.

---

## Contact

For questions or support, please open an issue or contact the course instructor.

---