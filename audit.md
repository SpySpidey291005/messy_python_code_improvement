# Code Audit Checklist – Student Marks Report

## 1. Project Information

| Item                 | Details                                                                |
| -------------------- | ---------------------------------------------------------------------- |
| Project Name         | Student Marks Report                                                   |
| Programming Language | Python                                                                 |
| AI Tool Used         | Cursor AI                                                              |
| Number of Students   | 5                                                                      |
| Number of Subjects   | 3                                                                      |
| Main Purpose         | Calculate student totals, averages, grades, class average, and topper. |

## 2. Code Audit Checklist

| S. No. | Audit Item            | Verification Criteria                                              | Status  |
| -----: | --------------------- | ------------------------------------------------------------------ | ------- |
|      1 | Student Data          | Contains marks for all five students.                              | ✅ Fixed |
|      2 | Subject Marks         | Processes all three subject marks for each student.                | ✅ Fixed |
|      3 | Total Calculation     | Correctly calculates the sum of all three subject marks.           | ✅ Fixed |
|      4 | Average Calculation   | Correctly calculates the average by dividing the total by 3.       | ✅ Fixed |
|      5 | Grade A               | Assigns A for averages of 90 or above.                             | ✅ Fixed |
|      6 | Grade B               | Assigns B for averages of 80 or above but below 90.                | ✅ Fixed |
|      7 | Grade C               | Assigns C for averages of 70 or above but below 80.                | ✅ Fixed |
|      8 | Grade D               | Assigns D for averages of 60 or above but below 70.                | ✅ Fixed |
|      9 | Grade F               | Assigns F for averages below 60.                                   | ✅ Fixed |
|     10 | Student Report        | Displays student names, totals, averages, and grades clearly.      | ✅ Fixed |
|     11 | Class Average         | Calculates the class average using the corrected student averages. | ✅ Fixed |
|     12 | Topper Identification | Identifies the student with the highest average.                   | ✅ Fixed |
|     13 | Output Formatting     | Displays the report in a readable format.                          | ✅ Fixed |

## 3. Output Verification Checklist

| S. No. | Student | Total Marks | Average | Grade | Status     |
| -----: | ------- | ----------: | ------: | :---: | ---------- |
|      1 | Rahul   |         258 |   86.00 |   B   | ✅ Verified |
|      2 | Priya   |         205 |   68.33 |   D   | ✅ Verified |
|      3 | Amit    |         269 |   89.67 |   B   | ✅ Verified |
|      4 | Sneha   |         173 |   57.67 |   F   | ✅ Verified |
|      5 | Vikram  |         249 |   83.00 |   B   | ✅ Verified |

## 4. Final Report Verification

| S. No. | Verification Item    | Expected Result                         | Status     |
| -----: | -------------------- | --------------------------------------- | ---------- |
|      1 | Total Calculation    | All three subject marks are included.   | ✅ Fixed    |
|      2 | Average Calculation  | Total marks divided by 3.               | ✅ Fixed    |
|      3 | Grade Classification | Grades follow the specified thresholds. | ✅ Fixed    |
|      4 | Class Average        | 76.93                                   | ✅ Verified |
|      5 | Topper               | Amit – 89.67 average                    | ✅ Verified |
|      6 | Report Formatting    | Clear and readable output.              | ✅ Fixed    |

## 5. Final Audit Summary

| Audit Parameter          | Result                               |
| ------------------------ | ------------------------------------ |
| Total Calculation        | ✅ Fixed                              |
| Average Calculation      | ✅ Fixed                              |
| Grade Classification     | ✅ Fixed                              |
| Report Formatting        | ✅ Fixed                              |
| Class Average            | ✅ Verified                           |
| Topper Identification    | ✅ Verified                           |
| AI-Assisted Debugging    | Cursor AI                            |
| **Overall Audit Status** | **✅ ALL IDENTIFIED ERRORS RESOLVED** |

**Conclusion:** The identified code issues have been addressed using Cursor AI. The corrected calculations, grade classification, report formatting, class average, and topper identification are reflected in this audit checklist.
