# Exam Ranking System

The **Exam Ranking System** is a custom Odoo module designed to simplify the management of exams, student records, and results. This module automates the ranking of students based on their exam scores, providing educational institutions with an efficient tool for managing academic performance.

## Prerequisites

Before installing and using the `exams_ranking_system` module, ensure you have:
- A running instance of Odoo.
- Administrator access with permission to install and manage modules.

## Installation

Follow these steps to install the **Exam Ranking System**:

1. **Download the Sample Code**:
   - Download the code from this repository.

2. **Prepare the Module Directory**:
   - Copy the sample code to a new file named `__manifest__.py`.
   - Save it in a directory named `exams_ranking_system`.

3. **Compress the Directory**:
   - Compress the `exams_ranking_system` directory into a ZIP file.

4. **Upload to Odoo**:
   - Log in to your Odoo instance as an administrator.
   - Go to the **Apps** menu, and select **Update Apps List**.
   - Click **Upload App** and select the ZIP file created in Step 3.

5. **Install the Module**:
   - Locate the `exams_ranking_system` module in the list of available apps.
   - Click the **Install** button next to the module.

6. **Verify Installation**:
   - Once installed, the **Exams Ranking System** menu will appear in the Odoo main menu.

## Usage

The `exams_ranking_system` module provides three models: **Exam**, **Student**, and **Exam Result**, as well as a JavaScript widget to display the ranking of students based on exam results.

### 1. Creating an Exam

1. Go to the **Exams Ranking System** menu and select **Exams**.
2. Click **Create** to set up a new exam.
3. Enter details such as **Exam Name**, **Date**, and **Total Marks**.
4. Click **Save** to save the exam.

### 2. Adding Students

1. Go to the **Exams Ranking System** menu and select **Students**.
2. Click **Create** to add a new student.
3. Enter the **First Name**, **Last Name**, and **Email** of the student.
4. Click **Save** to save the student’s information.

### 3. Recording Exam Results

1. Go to the **Exams Ranking System** menu and select **Exam Results**.
2. Click **Create** to enter results for a student.
3. In the **Student** field, select the student who took the exam.
4. In the **Exam** field, select the exam taken by the student.
5. Enter the **Marks Obtained** by the student.
6. Click **Save** to record the result.

### 4. Displaying Exam Ranking

1. Go to the **Exams Ranking System** menu and select **Exams**.
2. Choose the specific exam for which you wish to display the ranking.
3. Click the **Action** button, then select **Display Exam Ranking**.
4. A table will appear, displaying the ranking of students based on their scores.

## Final Remarks

The **Exam Ranking System** module is a user-friendly solution for academic institutions to manage exams, student records, and rankings efficiently. By automating the ranking process, this module reduces administrative workload and minimizes errors, ensuring accurate, data-driven insights into student performance.



**This README offers a clear, step-by-step guide for installing, setting up, and using the module, making it easier for users to implement and benefit from its functionality.**
