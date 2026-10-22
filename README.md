# messy_python_code_improvement

# Student Marks Report – Python

## Overview

This Python program processes student marks to generate a report containing each student's total marks, average marks, and grade. It also calculates the class average and identifies the student with the highest average.

## Student Data

The program contains marks for five students:

| Student | Subject 1 | Subject 2 | Subject 3 |
| ------- | --------: | --------: | --------: |
| Rahul   |        78 |        88 |        92 |
| Priya   |        65 |        71 |        69 |
| Amit    |        90 |        94 |        85 |
| Sneha   |        55 |        60 |        58 |
| Vikram  |        82 |        79 |        88 |

## Functions

### 1. `f(x)`

Calculates the total of the three subject marks by adding the values at indices 1, 2, and 3 of the student's data list.

### 2. Grade Classification

The program assigns grades according to the student's average marks:

| Average Marks            | Grade |
| ------------------------ | ----- |
| 90 or above              | A     |
| 80 or above but below 90 | B     |
| 70 or above but below 80 | C     |
| 60 or above but below 70 | D     |
| Below 60                 | F     |

## Features

* Calculates each student's total marks.
* Calculates each student's average marks.
* Assigns grades based on average marks.
* Displays a report for all students.
* Calculates the class average.
* Identifies the topper based on the highest average marks.

## How to Run

Run the Python program using:

```bash
python filename.py
```

Replace `filename.py` with the name of the Python file containing the code.

## Output

```text
REPORT
Rahul12588.0B
Priya20568.33333333333333D
Amit26989.66666666666667B
Sneha17357.666666666666664F
Vikram24983.0B
Class average:76.93333333333334
Topper:Amit89.66666666666667
```

## Summary

The program generates a student marks report, class average, and topper information using Python lists, loops, conditional statements, and functions.
