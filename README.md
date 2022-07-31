# Pewlett-Hackard-Analysis

## Overview of the Analysis

For this analysis we are working with a company named Pewlett Hackard. This is a large company with many thousands of employees. The management at the compnay is concerned that their workforce is aging and they may be facing a "silver tsunami". According to Wikipedia a "silver tusnami" is a metaphor used to describe an aging population. The specific concerns for Pewlett Hackard are, firstly they are thinking of offering retirement packages for employees who will be retiring in the future and secondly, they need to consider the positions that will need be filled in the near future.

Pewlett Hackard did not have any databases, instead their employee and related data was stored in six csv files. For the analysis we needed to create a database, import the tables and conduct a varieity of different analysis including the number of employees retiring by title and the employees available for the mentorship program.

### Data Sources and Software
The following data files (in csv format) were provided:
 - departments.csv
 - dept_emp.csv
 - dept_manager.csv 
 - employees.csv
 - salaries.csv
 - titles.csv

The analysis was conducted using PostgreSQL 11 and pgAdmin 4

## Results

As part of the analysis into employment at Pewlett Hackard a number of queiries and tables were created. Some of the major results of the analysis are: 

 - Many of the employees who are eligible for retirement have held multiple positions at Hewlett Packard during their tenure at the company. There are some employees who have had up to three unique job titles during their employment and the first year of employment for some employees is 1985. This shows that there is a lot of institutional knowledge at Pewlett Hackard and the company does need to make sure that knowledge is passed on to employees as older employees retire.

 - The analysis of unique titles shows us that we have 72,458 employees who are eligible for retirement based on their age. This can be seen below in the result of the query and in the exported table.


![Ret_unique_query](https://github.com/kkoehn8/Pewlett-Hackard_Analysis/blob/main/Ret_Unique_Query.png)
![ret_unique_table](https://github.com/kkoehn8/Pewlett-Hackard_Analysis/blob/main/Ret_Unique_Table.png)

 - One of the points of analysis was to perform a count of the retiring titles. The results as shown below demonstrate that a large portion of the retiring employees (Senior Engineer = 25,916 and Senior Staff = 24,926) are senior level staff. This result should not be a surprise, we would expect that as employees reach retirement age they will be more senior level staff, however it should remind Pewlett Hackard management that they will need more employees who are capable of stepping into senior level roles to compensate for the retiring employees.

![retiring_titles](https://github.com/kkoehn8/Pewlett-Hackard_Analysis/blob/main/Retiring_Titles.png)

 - When looking at the employees who are eligible for mentorship we notice that there are only 1,549 employees who currently qualify.

## Summary

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."



 - How many roles will need to be filled as the "silver tsunami" begins to make an impact?



 - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         qx           







