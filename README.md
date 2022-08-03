# Pewlett-Hackard-Analysis
## Overview 
### Purpose
Pewlett Hackard has a large number of employees who will be retiring in the coming years, in order to be prepared for this, they tasked us with sifting through various files to define who will be leaving and from what department, and who is eligible for the mentorship program for incoming staf members. 
#### Tasks to complete
 - Parse through data, and combine tables to shows specific data sets; tables include
    1. The titles of people who are retiring.
    2. Refactoring the title's table to show the most recent title held by employees.
    3. A table that shows the number of people retiring per title.
    4. A table that holds employees who are eligible for a mentorship programs, this includes staff who are born in the year 1965 and shows their current title. 
#### Resources
 - Data sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
 - Software:
   - pgAdmin4
   - PostgreSQL 
   - quickdatabasediagrams.com
## Results
 - The table retirement_titles.csv contains a list of 133,776 names that are expected to retire, it contains their title, first and last name and dates from when they began to their current work date, some have already left the company, so they won't need to be considered.
 - The unique_titles.csv narrows down the previous list and contains the same list of employees, but holds only their most recent title in the company as opposed to every title they have held while working for Pewlett-Hackard, the number of employees retiring on list descreased significantly to 72,459 employees. 
 - The retiring_titles.csv shows the number of people retiring per title. Using the previous data set, the number of employees, and their corresponding titles were grouped together as seen in the image below. Senior engineer and senior staff members are set to lose the most people, current engineers will also be losing numbers, so they will need to focus recruitment in those areas.
 https://github.com/AbiE216/Pewlett-Hackard-Analysis/issues/1#issue-1327502188

