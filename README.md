# JEE Main Applicant Record Management System Documentation
## Table of Contents
### Introduction
### Setup
  - ### Database Creation
### Functions
  - ### Create Database and Table
  - ### Insert Applicant Information
  - ### Display Applicant Information
  - ### Update Applicant Information
  - ### Delete Applicant Information
  - ### Alter Table
  - ### Drop Table
### Usage
### Conclusion

## 1. Introduction <a name="introduction"></a>
The JEE Main Applicant Record Management System is a console-based application designed to manage applicant information for the Joint Entrance Examination (JEE) Main. This documentation provides an overview of the system's features, setup instructions, available functions, and usage examples.

## 2. Setup <a name="setup"></a>
### Database Creation <a name="database-creation"></a>
To use the JEE Main Applicant Record Management System, follow these steps:

Install MySQL and the MySQL Connector module.
Run the provided script to create the database and table.
Use the various functions to manage applicant information.

## 3. Functions <a name="functions"></a>
### Create Database and Table <a name="create-database-and-table"></a>
Use the create() function to create the necessary database and table for storing applicant records.

### Insert Applicant Information <a name="insert-applicant-information"></a>
Use the insert() function to insert applicant information, including S.No., Application Number, Candidate Name, State, and Category.

### Display Applicant Information <a name="display-applicant-information"></a>
Use the display() function to display the full table of applicant information. You can also display information based on different criteria such as S.No., Application Number, Candidate Name, State, or Category using specific display functions.

### Update Applicant Information <a name="update-applicant-information"></a>
Use the updatesno(), updatename(), updatestate(), and updatecat() functions to update applicant information based on different criteria.

### Delete Applicant Information <a name="delete-applicant-information"></a>
Use the deletesno(), deleteappno(), deletename(), deletestate(), and deletecat() functions to delete applicant information based on different criteria.

### Alter Table <a name="alter-table"></a>
Use the alteradd(), altermod(), and alterrem() functions to add, modify, or remove columns from the applicant table.

### Drop Table <a name="drop-table"></a>
Use the droptable() function to remove the entire applicant table from the database.

## 4. Usage <a name="usage"></a>
1. Run the script to create the database and applicant table.
2. Choose the desired action:
  - Create: Create the database and applicant table.
  - Insert: Insert applicant information.
  - Display: Display applicant information using different criteria.
  - Update: Update applicant information based on different criteria.
  - Delete: Delete applicant information based on different criteria.
  - Alter: Add, modify, or remove columns from the applicant table.
  - Drop Table: Remove the entire applicant table from the database.

## 5. Conclusion <a name="conclusion"></a>
The JEE Main Applicant Record Management System offers a practical solution for managing applicant information for the Joint Entrance Examination (JEE) Main. By following the setup instructions and utilizing the provided functions, users can effectively manage, retrieve, update, and delete applicant records in the MySQL database.
