# Grading Manager

Grading Manager is a Swift-based command-line application that allows instructors to manage and analyze student grades efficiently. The application reads data from a CSV file, performs various operations like calculating averages, finding the highest/lowest grades, and updating student grades.

## Features

- Display the grade of a specific student.
- Display all grades for a particular student.
- Display all grades of all students.
- Calculate the class average.
- Calculate the average grade for a specific assignment.
- Find the student with the lowest grade.
- Find the student with the highest grade.
- Filter students based on a grade range.
- Update a student's grade for a specific assignment.

## Prerequisites

- macOS with Swift installed (Xcode can be used to run Swift code)
- CSV file containing student names and grades in the correct format

## How to Use

### 1. Prepare the CSV File

Create a file named `students.csv` and place it in the same directory as your Swift file. The CSV file should contain student names and grades in the following format:

```csv
John Doe, 85, 90, 92, 88, 76, 80, 95, 89, 91, 93
Jane Smith, 78, 80, 85, 87, 75, 70, 76, 72, 84, 88
Each row should contain the student's name, followed by 10 grades.

2. Setup the Project
Clone this repository or create a new file grading_man.swift in your local directory.
Add the students.csv file in the same folder as the Swift code.
3. Run the Program
To run the program, use the following steps:

Open a terminal window.

Navigate to the directory containing the Swift file and CSV.

Run the Swift script:

bash
Copy
Edit
swift grading_man.swift
4. Interact with the Application
You will be presented with a menu of options, such as:

Display grades for a specific student.
Calculate the class average.
Update a student's grade.
Exit the program.
Use the numbers corresponding to each option to interact with the application.

Example Output
bash
Copy
Edit
Welcome to the Grade Manager!

What would you like to do? (Enter the number):
1. Display grade of a single student
2. Display all grades for a student
3. Display all grades of ALL students
4. Find the average grade of the class
5. Find the average grade of an assignment
6. Find the lowest grade in the class
7. Find the highest grade of the class
8. Filter students by grade range
9. Update a student's grade
10. Quit
Sample Output for Displaying a Student's Grade:
bash
Copy
Edit
Enter your choice (1-10): 1

Which student would you like to choose?
John Doe

John Doe's grade in the class is 88.50
Contributing
If you find any bugs or would like to improve the program, feel free to fork the repository, make changes, and create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
