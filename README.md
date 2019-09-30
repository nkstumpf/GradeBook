# GradeBook
Week 4 Gateway Final JS Project

Features:

* Any additional HTML/CSS was added dynamically using Javascript *

- Add assignments to the page dynamically.

- Remove assignments from the page dynamically.

- Add new students to the user's "roster".

- Adding a student also properly formats their first and last name in the roster dropdown menu.

- Adding a student generates a student profile that will display when that student is selected.

- Adding a student generates a unique username for the student consisting of their first initial and last name.

- The assignments form will only submit an assignment if the user has selected a student from the dropdown menu.

- If the user does not have a student selected the app will alert the user.

- The assignments form will only submit an assignment if the user has all fields completed.

- If the user does not have all fields filled out in the form the app will alert the user.

- Assignments are students specific.

- If the user adds an assignment to the table it also stores it to the data structure of the student that is currently selected.

- If the user deletes an assignment- It is also deleted from the data structure of the student that is currently selected.

- The table will repopulate data dynamically based on which student is currently selected.

- This flexibility allows the user to add multiple students to the roster and their data will save independently.

- Since data saves independently the user can add multiple assignments to multiple students simultaneously and all student data is preserved when switching between student profiles. This persists until the user refreshes the browser.

- Each students GPA will calculate dynamically based on how many assignments the user has added to the student's profile.

- GPA also adjusts when the user deletes assignments.
