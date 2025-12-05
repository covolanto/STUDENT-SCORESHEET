# STUDENT-SCORESHEET

My Java program is a structured report-card generator designed to collect, process, and display the academic performance of up to twelve students. It begins by creating a `Scanner` object to read user input and defining several arrays to store information for each student, including their names, subject marks, total scores, and final ranks. Each array is sized using a constant `MAX = 12`, ensuring the program can handle a maximum of twelve students as required.

The program then collects general school information such as the school name, teacher name, grade, and year. After this setup, the user is prompted to enter the number of students whose marks will be recorded. For each student, the program requests the marks for six subjects: English, Math, History, Geography, Science, and Programming. These values are then stored in separate arrays.

After recording all marks, the program calculates each student’s total by summing the six subject scores. It then assigns a rank based on the total score using standard grading thresholds. If a student scores at least 540, they receive an A; scores above 480 earn a B, and so forth. Each rank assignment is also counted to generate rank statistics at the end of the report.

Next, the program computes the total and average marks for each subject by looping through all student entries. These values help provide a summary of class performance.

For output, the program uses formatted printing with `System.out.printf()` to align columns properly. This creates a clean and readable table displaying student names, subject marks, totals, and ranks. Summary rows for subject totals and averages follow beneath the student data. Finally, the program prints the number of students who achieved each rank category (A through F), completing the report.

Overall, your code effectively combines arrays, loops, input handling, conditionals, and formatted output to generate a full academic report card system.
