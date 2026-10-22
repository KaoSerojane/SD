# Section D

Project overview

The system is designed to manage student records. It allows you to add, remove, update, search and calculate averages. The system uses functions, dictionaries and validation as well as error handling techniques.

Set up instructions

Have pycharm application installed

run python main.py

Feature list:

Adds new students

stores grades for all subjects

displays individual student records

displays all student records

update students 

remove students

Function architecture:

add_student()

get_valid_grade()

calculate_average()

display_student()

display_student_summary()

search_and_uodate()

remove_student()

Example input/output:

Enter choice: 3

Student Summary

Name: kao
Maths : 55.0
Science : 66.0
English : 77.0
Average: 66.0

Assumptions:

names are case sensetive

Grades must range between 0 and 100

subjects are maths, english and science

summary table

<img width="405" height="153" alt="image" src="https://github.com/user-attachments/assets/e462cd1c-b7bc-4587-a374-0fbdfc117ac1" />

Known issues

Lists cannot be changed in runtime- we can solve this by using a fixed set of subjects
Duplicate student names may overwrite data- solve this by encouraging use of unique names

Refrences
W3Schools. Python Tutorial. https://www.w3schools.com/python/


