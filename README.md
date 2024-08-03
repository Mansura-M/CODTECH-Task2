**Name**:Mansura M
**Company**:CODTECH IT SOLUTIONS
**ID**:CT4PP4214
**Domain**:Python Programming
**Duration**:July 5th,2024 to August 5th,2024
**Mentor**:

## Project Overview: Python GPA Grade Calculator

### Introduction
The Python GPA Grade Calculator is a command-line application that helps students calculate their GPA (Grade Point Average) and CGPA (Cumulative Grade Point Average) based on their subject grades and credit hours. The calculator is designed to handle multiple subjects and provide an accurate assessment of a student's academic performance on a 4.0 scale.

### Features
1. **User Input for Subjects and Grades:**
   - The program prompts the user to input the number of subjects.
   - For each subject, the user inputs the subject name and the corresponding grade.

2. **Grade Conversion:**
   - Grades are stored as numeric values.
   - The average grade is calculated based on these numeric values.
   - Grades are converted to letter grades based on predefined ranges:
     - A: 90-100
     - B: 80-89
     - C: 70-79
     - D: 60-69
     - F: Below 60

3. **GPA Calculation:**
   - The program calculates the GPA for the current term based on the weighted average of grades and their respective credit hours.

4. **CGPA Calculation:**
   - The program calculates the CGPA by scaling the GPA using a predefined factor.

5. **Result Display:**
   - The program displays the average grade, overall letter grade, GPA for the current term, and CGPA.

### Implementation Details
- **Class Structure:**
  - The `grade_tracker` class encapsulates all the functionalities of the grade calculator, including methods for input handling, grade conversion, GPA calculation, and CGPA calculation.

- **Input Handling:**
  - The `input()` function captures user inputs for subjects, grades, and credit hours.
  - Methods within the class handle input validation and data storage.

- **Grade Conversion:**
  - The `grade_of_each_sub` and `assigned_value` methods handle the conversion of numeric grades to letter grades and GPA points, respectively.

- **GPA and CGPA Calculation:**
  - The `gpa` method calculates the GPA using the formula:
    \[
    \text{GPA} = \frac{\sum (\text{Grade Points} \times \text{Credit Hours})}{\sum \text{Credit Hours}}
    \]
  - The `cgpa` method scales the GPA to compute the CGPA.



### User Experience
The GPA Grade Calculator is designed to be intuitive and user-friendly. The following steps outline the typical user experience:

1. **Subject Input:**
   - The user inputs the number of subjects.
   - For each subject, the user inputs the subject name and grade.

2. **Grade Calculation:**
   - The program calculates the average grade and overall letter grade.

3. **GPA Calculation:**
   - The user inputs the credit hours for each subject.
   - The program calculates the GPA based on the grades and credit hours.

4. **CGPA Calculation:**
   - The program calculates the CGPA based on the GPA.

5. **Result Display:**
   - The program displays the average grade, overall letter grade, GPA for the current term, and CGPA.

### Example Workflow
1. The user inputs the number of subjects (e.g., 3).
2. For each subject, the user inputs the subject name (e.g., Math, Science, History) and grade (e.g., 85, 90, 78).
3. The program calculates the average grade (e.g., 84.33) and overall letter grade (e.g., B).
4. The user inputs the credit hours for each subject (e.g., 3, 4, 2).
5. The program calculates the GPA (e.g., 3.29) and CGPA (e.g., 8.225).
6. The program displays the results:
   - Average grade: 84.33
   - Overall grade: B
   - GPA: 3.29
   - CGPA: 8.225

### Conclusion
The Python GPA Grade Calculator project is a valuable tool for students to calculate their academic performance on a 4.0 scale. It provides a comprehensive learning experience for beginners, helping them to grasp essential programming concepts in Python. By offering flexible input handling, accurate GPA and CGPA calculations, and clear result displays, the project ensures a smooth and user-friendly experience, making it a valuable addition to any beginner's programming portfolio.

![Screenshot (691)](https://github.com/user-attachments/assets/622a401b-6ab1-4dab-9590-f4b3af9d8109)

