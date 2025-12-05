# STUDENT-SCORESHEET

Our project is a group effort to build a Java program that generates a report card by collecting school, teacher, and student information. We use the Scanner class to handle user input, starting with text entries like names and then moving to numeric scores. Because of the way Scanner processes strings and integers, we discovered issues with leftover newline characters causing input mismatches. As a team, we identified that the fix is to consistently use nextLine() for text and clear the buffer before reading numbers.

And here is the output
![OUTPUT OF THE CODE](https://github.com/user-attachments/assets/4edbcad8-e0d4-425b-88b5-141e28da66fe)
