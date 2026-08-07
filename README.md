# PrepTrack — Placement Preparation Performance Analyzer

## Project Overview

PrepTrack is a Python-based console application designed to assess a student's readiness for placement interviews through a seven-day coding practice evaluation. It gathers essential student information, including attendance, graduation year, project completion status, profile verification, and daily practice scores.

After collecting the required details, the application validates every input, analyzes coding performance, calculates the average score, identifies strengths and weaknesses, detects critical performance issues, and determines the student's placement readiness. A detailed report is then generated with the final status, primary blocker (if any), and suggested next action.

---

# Features Implemented

- Student information collection
- Name validation
- Registration number input
- Graduation year verification
- Attendance validation (0–100%)
- Project completion verification
- Profile verification check
- Seven-day coding practice evaluation
- Practice score validation (`0–100` or `-1` for absent)
- Absent day handling
- Performance classification:
  - Strong
  - Satisfactory
  - Needs Improvement
  - Critical
- Attempted, absent, passed, and failed day counting
- Highest and lowest score identification
- First critical score tracking
- Total and average score calculation
- Placement eligibility assessment
- Final performance report with blocker analysis and recommendation

---

# Python Concepts Used

This project demonstrates the use of the following Python concepts:

- Variables and Constants
- Data Types (`int`, `float`, `str`, `bool`)
- User Input and Output
- Type Conversion
- Arithmetic Operations
- Comparison Operators
- Logical Operators
- Assignment Operators
- Conditional Statements (`if`, `elif`, `else`)
- Nested Conditions
- `for` Loop
- `while` Loop
- `continue` Statement
- Boolean Expressions
- String Functions (`strip()`, `lower()`)
- Exception Handling (`try`, `except`)
- Formatted String Literals (f-strings)

---

# How to Run the Program

Execute the application using:

```bash
python main.py
```

or

```bash
python3 main.py
```

Enter the requested student details and seven-day practice scores. Once all inputs are provided, the program automatically evaluates the performance and displays the placement readiness report.

---

# Test Result Summary

The project was tested using multiple scenarios to ensure proper validation and accurate placement readiness evaluation.

### Test Scenarios

- Blank student name
- Blank registration number
- Invalid graduation year
- Attendance outside the valid range
- Incorrect Yes/No responses
- Invalid practice scores
- Absent practice day (`-1`)
- No attempted practice days
- Presence of critical scores
- Less than six attempted practices
- Fewer than four passed practices
- Average score below required threshold
- Attendance below 75%
- Incomplete project
- Profile not verified
- Student satisfying every eligibility condition

### Outcome

All test scenarios produced the expected results. Input validation, score processing, placement eligibility checks, and report generation worked successfully under all tested conditions.

---

# Individual Contribution

**Name:**

Deepa Bhavyasri Sonti

**Repository URL:**

https://github.com/Deepbhavyasrisonti/prepTrack-Deepa

**My Contribution:**

I independently designed and implemented the complete PrepTrack application. My work included developing the validation logic, coding practice analysis, placement eligibility evaluation, and report generation while ensuring the application remains simple, reliable, and easy to use.

**Modules Implemented:**

- Student profile management
- Attendance validation
- Project completion verification
- Profile verification
- Seven-day coding practice evaluation
- Practice score validation
- Performance classification
- Pass/fail analysis
- Highest and lowest score calculation
- Critical score identification
- Average score computation
- Placement readiness evaluation
- Final report generation

**Python Concepts Applied:**

- Variables
- `for` and `while` loops
- Conditional statements
- Boolean logic
- Exception handling
- Input validation
- Arithmetic calculations
- Logical operators
- String manipulation
- f-strings

**Most Challenging Part:**

The most challenging task was implementing the placement readiness logic while maintaining the correct priority of conditions. Another challenge was accurately processing absent days without affecting the overall calculations.

**Issue Faced:**

During development, I encountered difficulties handling invalid inputs and ensuring that the average score considered only attempted practice days. Maintaining accurate highest and lowest score tracking was also challenging when absent days were present.

**Solution Implemented:**

I solved these issues by incorporating `while` loops for repeated validation, `try-except` blocks for handling invalid inputs, and separate counters for attempted and absent practice days. This ensured reliable calculations and consistent report generation.

---

# Code Review Completed

The project was reviewed after implementation to verify its correctness and maintainability.

The review covered:

- Input validation
- Logic correctness
- Code readability
- Variable naming conventions
- Placement eligibility rules
- Output presentation

The review confirmed that the application performs as expected and follows clean coding practices.

---

# Feedback Received

The following suggestions were provided during the review:

- Improve the presentation of the final report.
- Validate every user input more effectively.
- Avoid displaying score-related information when no practice attempts exist.
- Simplify the placement eligibility conditions.
- Handle invalid inputs more gracefully.

---

# Improvements Made

Based on the review comments, I implemented the following improvements:

- Enhanced input validation using loops and exception handling.
- Improved the layout of the final report.
- Added proper validation for Yes/No responses.
- Prevented division-by-zero errors during average calculation.
- Displayed highest and lowest scores only when valid practice attempts exist.
- Improved blocker identification and recommendation messages.
- Added comments and organized the code for better readability.

---

# Conclusion

Developing PrepTrack strengthened my understanding of Python fundamentals and practical problem-solving techniques. The project improved my knowledge of validation, control structures, logical decision-making, and report generation while emphasizing the importance of writing clean, structured, and maintainable code.

## Thank You

Thank you for taking the time to review my PrepTrack project. Your feedback is greatly appreciated and will help me continue improving my programming skills.
