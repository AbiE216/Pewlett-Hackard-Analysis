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
 - The unique_titles.csv narrows down the previous list and contains the same list of employees, but holds only their most recent title in the company as opposed to every title they have held while working for Pewlett-Hackard, the number of employees retiring on list descreased significantly to 72,458 employees. 
 - The retiring_titles.csv shows the number of people retiring per title. Using the previous data set, the number of employees, and their corresponding titles were grouped together as seen in the image below. Senior engineer and senior staff members are set to lose the most people, current engineers will also be losing numbers, so they will need to focus recruitment in those areas.
![retiring_titles](https://user-images.githubusercontent.com/106715300/182660248-3dfbaa9e-e0f5-4e25-8424-8bcccd11c643.png)
- The final table, membership_eligibility.csv, contains a list of current employees that are eligible for a new employee mentorship program. This list contains the name of 1,549 employees. As they are mostly Senior staff and Senior engineers this will ease a portion of the loss that is coming, and will hopefully get new employees up to speed faster. 
## Summary 
- As the "silver tsunami begins" PH is going to be looking to fill about 72.5k positions. They will need to prepare to fill a lot of lower level positions and move up their current staff into higher level positions. 
- For there to be enough people to mentor incoming employees, lets say there are 21,614 entry-level positions to be filled, with 1,549 employees eligible for the mentorship program, each senior employee would be responsible for mentoring about 14 people. This is probably not going to give the preferred results and they should consider adding another year or even two into the program, as a 7:1 or 4:1 ratio would provide better long term results. 
- It would be important to look year by year for outgoing employees. They are not likely to leave all at once, so having a time line will give better insights on when positions need to be filled. 
- Finally PH should lool into the number of younger people in different positions. Knowing if you can replace the outgoing senior employees with employees who have worked there for a certain amount of time, will tell you how many more entry level people you need, and how many current employees can be promoted. This number will then affect your mentoring program, and the potential need for adding many many more people into it. 



