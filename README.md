StudentGradesTracker
Details:
Name: JACK ROBIN J
Company: CODETECH IT SOLUTIONS
ID: CT08TGY
Domain: Java Programming
Duration: January to February 2025
Overview:
The StudentGradesTracker is a Java program designed to track a student's grades across multiple subjects, compute the average grade, and provide a letter grade based on the average score.

Features:
The program allows the user to input the number of subjects and the grade for each subject.
It calculates the average grade for all the subjects.
It then converts the average grade to a letter grade (A, B, C, D, or F) based on standard grading criteria.
Instructions:
Requirements:
Java Development Kit (JDK) 8 or higher.
Running the Program:
Compile the Program:
Open a terminal or command prompt and navigate to the directory where the StudentGradesTracker.java file is located. Compile the program using the following command:

nginx
Copy
Edit
javac StudentGradesTracker.java
Run the Program:
After compiling, run the program using the following command:

nginx
Copy
Edit
java StudentGradesTracker
Follow the Prompts:
The program will ask for:

The number of subjects.
The grade for each subject (as a numeric input).
After entering the grades, the program will display:

The average grade.
The letter grade corresponding to the average.
Example:
Input:
yaml
Copy
Edit
Enter the number of subjects: 3
Enter grade for subject 1: 85
Enter grade for subject 2: 92
Enter grade for subject 3: 78
Output:
yaml
Copy
Edit
Average Grade: 85.0
Letter Grade: B
Code Explanation:
Input Handling:
The program uses Scanner to take user input for the number of subjects and the grades for each subject.

Grade Calculation:
It sums the grades for all subjects and computes the average.

Letter Grade Assignment:
The method getLetterGrade(double average) is used to convert the average grade to a corresponding letter grade (A, B, C, D, or F) based on the following criteria:

90 and above: A
80 to 89: B
70 to 79: C
60 to 69: D
Below 60: F
License:
This project is created for educational purposes and may be freely used, modified, and distributed for personal or academic use.

Author:
JACK ROBIN J
Company: CODETECH IT SOLUTIONS
