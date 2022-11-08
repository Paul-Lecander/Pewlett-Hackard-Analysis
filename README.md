# Pewlett Hackard 'Silver Wave' Analysis With SQL

## Overview

Pewlett Hackard is a company that has an issue with many employees nearing retirement. To prepare for a wave of departing employees, this challenge was made to address the following using PosteSQL:

1) Determining how many retiring employees per job title</br>
2) Identifying employees that were eligible to participate in a mentorship program</br>

## Results

- In the first part of the analysis, a query was created to illustrate the number of employees in the range of retirement per job title.</br>

![retiring_titles.png](https://github.com/Paul-Lecander/Pewlett-Hackard-Analysis/blob/main/retiring_titles.png.png)</br>

- This table shows there are 72,458 employees from Pewlett Hackard that are in the range for retirement and from 7 different titles/roles.

- The second part of the analysis was to identify which employees were eligible to participate in the mentorship program. 
- After creating the mentorship eligibility data frame, it shows that all employees from the first part are eligible for the mentorship program.

## Summary

- Employees that are eligible to retire come out to be 72,458 and over a third of them are engineers. 
- All employees that are eligible to retire are also eligible for the mentorship program.
- A possible refinement to the mentorship program could be using a query on how long an employee has been there (i.e. greater than 10 years) to be eligible for mentorship.
- Another table that could provide more insight is employees not eligible to retire who have been at the company for an extended period, that would make them good canidates to be in the mentorship program.

