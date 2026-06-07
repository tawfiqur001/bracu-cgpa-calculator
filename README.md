# BRACU CGPA Calculator with Repeat / Retake Adjustment

A simple BRACU CGPA calculator built for students who need accurate repeat and retake course adjustment. Unlike basic CGPA calculators, this tool lets you enter previous grades, new grades, completed credits, and admission-based retake rules to estimate your updated BRAC University CGPA more easily.

## Features

* Calculate CGPA based on BRAC University grading system
* Support for previous CGPA and completed credits
* Add unlimited regular courses
* Add repeat/retake courses with automatic grade adjustment
* **Admission-aware repeat policy** - automatically applies the correct rule based on when you were admitted
* Mobile-friendly responsive design
* Clean and minimal user interface
* No installation required - runs directly in the browser

## How CGPA is Calculated

The calculator uses the official BRAC University formula:

$$
\text{CGPA} = \frac{\sum (\text{Grade Points} \times \text{Credits})}{\sum \text{Credits Attempted}}
$$

### Repeat / Retake Courses

BRAC University applies different policies depending on admission semester:

| Admitted | Grade Applied |
|----------|--------------|
| Before Summer 2025 | The **better** of the two grades is counted |
| Summer 2025 or after | The **latest** (most recent) grade is counted |

The calculator asks which applies to you and adjusts automatically.

## Usage

### Previous Record

Enter your current CGPA and total completed credits. If you are calculating from the beginning, leave these fields empty.

### Regular Courses

For each course:
* Enter the course credit
* Select the obtained grade

### Repeat / Retake Courses

* Select your admission period using the toggle at the top of the section
* For each repeated course, enter the credit, previous grade, and new grade
* The calculator applies the correct grade automatically

### Calculate

Click **Calculate CGPA** to view your updated cumulative GPA.

## Grade Scale

| Grade | Grade Points |
|-------|-------------|
| A / A+ | 4.00 |
| A− | 3.70 |
| B+ | 3.30 |
| B | 3.00 |
| B− | 2.70 |
| C+ | 2.30 |
| C | 2.00 |
| C− | 1.70 |
| F | 0.00 |

## Language Used

* HTML5
* CSS3
* Vanilla JavaScript


## Disclaimer

This calculator is an unofficial student-made tool and is intended for estimation purposes only. Always verify your academic records through the official BRAC University student portal.

