# Setting up and Using the Odoo Module 'exams_ranking_system'

THE FOLLOWING ARE DETAILED INSTRUCTIONS ON INSTALLATION AND USAGE OF ODOO EXAM RANKING SYSTEM.

The 'exams_ranking_system' is a custom Odoo module for managing exams, students, and their results. 

This module provides a ranking system for exams taken by students. 

This README file provides detailed instructions on how to set up and use this module.

#Prerequisites

Before installing and using the 'exams_ranking_system' module, you should have the following:
A running instance of Odoo.
Access to the Odoo administrator account with permission to install modules.

#Installation

To install the 'exams_ranking_system' module, follow the steps below:
Download the sample code provided in this Repository.
Copy the sample code to a new file named _manifest_.py and save it in a directory named exams_ranking_system.
Compress the exams_ranking_system directory to a ZIP file.
Log in to your Odoo instance as an administrator.
Go to the Apps menu and select 'Update Apps List'.
Click the 'Upload App' button and select the ZIP file you created in step 3.
Once the app is uploaded, you should see the 'exams_ranking_system' module in the list of available apps.
Click the 'Install' button next to the 'exams_ranking_system' module to install it.
After installation, you should be able to see the 'Exams Ranking System' menu in the main menu of Odoo.

#Usage

The 'exams_ranking_system' module provides three models: Exam, Student, and ExamResult. These models are used to manage exams, students, and their results. Additionally, the module provides a JavaScript widget for displaying the exam ranking per student.
Creating an Exam
To create a new exam, follow the steps below:
Go to the 'Exams Ranking System' menu and select 'Exams'.
Click the 'Create' button to create a new exam.
Enter the exam name, date, and total marks.
Click the 'Save' button to save the new exam.
Creating a Student
To create a new student, follow the steps below:
Go to the 'Exams Ranking System' menu and select 'Students'.
Click the 'Create' button to create a new student.
Enter the student's first name, last name, and email.
Click the 'Save' button to save the new student.
Recording Exam Results
To record the results of an exam taken by a student, follow the steps below:

Go to the 'Exams Ranking System' menu and select 'Exam Results'.
Click the 'Create' button to create a new exam result.
Select the student who took the exam from the 'Student' field.
Select the exam taken by the student from the 'Exam' field.
Enter the marks obtained by the student in the 'Marks Obtained' field.
Click the 'Save' button to save the new exam result.
Displaying Exam Ranking per Student

To display the exam ranking per student, follow the steps below:

Go to the 'Exams Ranking System' menu and select 'Exams'.

Click on the exam for which you want to display the ranking.

Click the 'Action' button and select 'Display Exam Ranking' from the dropdown menu.

The exam ranking per student will be displayed in a table format.

Conclusion

The 'exams_ranking_system' module provides an easy-to-use system for managing exams, students, and their results
