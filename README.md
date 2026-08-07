# prepTrack-Deepa

# PrepTrack — Placement Preparation Performance Analyzer

## Project Overview

PrepTrack is a Python console application that analyzes a student's placement preparation performance over seven days of coding practice.

The application:
- Collects student details
- Validates all inputs
- Processes 7-day coding scores
- Classifies performance
- Calculates total and average scores
- Finds highest and lowest scores
- Detects the first critical score
- Evaluates placement readiness
- Displays the primary blocker and recommended next action

---

## Features

### Student Details
- Student Name
- Registration Number
- Graduation Year
- Attendance Percentage
- Project Completion Status
- Profile Verification Status

### Input Validation
- Non-empty student name
- Attendance between 0 and 100
- Yes/No validation
- Score validation (`-1` or `0-100`)

### Practice Analysis
- Seven-day coding practice tracking
- Handles absent days
- Score classification:
  - Strong (75–100)
  - Satisfactory (60–74)
  - Needs Improvement (40–59)
  - Critical (0–39)

### Statistics
- Attempted Days
- Absent Days
- Passed Days
- Failed Days
- Strong Days
- Satisfactory Days
- Needs Improvement Days
- Critical Days

### Performance Analysis
- Total Score
- Average Score
- Highest Score
- Lowest Score
- First Critical Score

### Placement Decision
- Graduation eligibility
- Attendance verification
- Practice completion
- Average score validation
- Critical score verification
- Project completion
- Profile verification

---

## Python Concepts Used

- Variables
- Data Types
- Input / Output
- Type Conversion
- Arithmetic Operators
- Relational Operators
- Logical Operators
- if-elif-else
- Nested Conditions
- while Loop
- for Loop
- break
- continue
- Boolean Expressions
- Counters
- Accumulators
- Defensive Programming

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/preptrack.git
cd preptrack
```

Run:

```bash
python main.py
```

or

```bash
python3 main.py
```

---

## Sample Test Results

| Test ID | Scenario | Expected | Status |
|---------|----------|----------|--------|
| TC-01 | All conditions satisfied | Ready for Mock Interview | Pass |
| TC-02 | Critical score | Critical Support Required | Pass |
| TC-03 | Practice less than 6 days | Practice Incomplete | Pass |
| TC-04 | Passed days below 4 | Insufficient Passed Practices | Pass |
| TC-05 | Average below 70 | Practice Improvement Required | Pass |
| TC-06 | Attendance below 75 | Attendance Improvement Required | Pass |
| TC-07 | Graduation not eligible | Graduation Criteria Not Met | Pass |
| TC-08 | Project incomplete | Application On Hold | Pass |
| TC-09 | Profile not verified | Application On Hold | Pass |
| TC-10 | All days absent | Practice Not Evaluated | Pass |

---

## Project Structure

```
PrepTrack/
│── main.py
│── README.md
```

---

## Technologies Used

- Python 3
- Antigravity
- Git
- GitHub

---

## Author

Deepa Bhavya Sri Sonti

GitHub: https://github.com/Deepbhavyasrisonti/prepTrack-Deepa

---

## License

This project is developed for educational and placement preparation purposes.
