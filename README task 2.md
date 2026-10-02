# Student Grade Calculator

## Veda Technology — AI & ML Internship

**Task:** Task 2 — Student Grade Calculator  
**Level:** 1 | **Day:** 2  
**Tools:** Python, Jupyter Notebook

## Objective
Create a Python program that assigns grades to students based on their marks using predefined grading conditions.

## Grading Logic
- 90–100 → A+
- 80–89 → A
- 70–79 → B
- 60–69 → C
- 50–59 → D
- 40–49 → E
- 0–39 → F
- Outside 0–100 → Invalid

## Approach
Student names and marks are stored in a Python dictionary. The `calculate_grade()` function uses `if`, `elif`, and `else` statements to assign a grade. It also validates that marks are between 0 and 100.

## Sample Output
```text
Student Grade Calculator
------------------------
Aman: 92 marks -> Grade A+
Priya: 85 marks -> Grade A
Rahul: 76 marks -> Grade B
Sneha: 68 marks -> Grade C
Vikas: 59 marks -> Grade D
Neha: 43 marks -> Grade E
Karan: 31 marks -> Grade F
```

## Concepts Practiced
- Python dictionaries
- Functions
- Conditional statements
- Input validation
- Iteration

## How to Run
Open `Student Grade Calculator.ipynb` in Jupyter Notebook or Google Colab and run the code cell.

## Deliverables
- `Student Grade Calculator.ipynb` — complete Python program and output
- `README.md` — grading logic, approach, and project explanation

## Interview Questions
1. **What is the purpose of if-elif-else?**  
   It checks multiple conditions and executes the block for the first condition that is true.

2. **How would you handle invalid marks?**  
   Check whether marks are below 0 or above 100 and return `Invalid`.

3. **Can conditional statements be used while processing datasets?**  
   Yes. They can be used to classify, filter, validate, and transform records.
