# Pewlett-Hackard-Analysis
### _silver tsunami_

## Overview of the analysis
Pewlett Hackard is a large company with close to 240,000 employees. With majority of its workforce nearing retirement it is important for Pewlett Hackard management to have an understanding on the retiring employees to plan for succession and the future with employees who are eligible for mentorship program. 

For this purpose, we perfrom a SQL based analysis on 2 metrics.
1.  The Retiring Employees by Title
2.  The Employees Eligible for the Mentorship Program

## Results
### Retiring Employees by Title
We perform a sequence of queries to arrive at the list of retiring employees. From the entire employee database we are filtering for 'active' employees whose were born between 1952 - 1955 (i.e. birth date between January 1, 1952 and December 31, 1955) who are due for retirement. We remove for duplicates to ensure we perform the analysis only on their recent titles. 
1.  There are around 72458 [employees](https://github.com/gopivasanth/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.csv) retiring which is approximately close to 30% of the active workforce.
2. [Title wise breakdown](https://github.com/gopivasanth/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv) of retiring employees show that there are nearly 36% of employees with title Senior Engineer and 34% with title Senior Staff.

This is indeed a challenging situation for Pewlett-Hackard and they term this '_silver tsunami_'

### Employees Eligible for Mentorship Program
Taking cue from the current challenge Pewlett Hackard formalizes a list of employees born in 1965 (birth date between January 1, 1965 and December 31, 1965) who are eligible for mentorship program.
1.  There are 1550 active employees born in 1965 with [mentorship eligibility](https://github.com/gopivasanth/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibilty.csv)

## Summary
While the analysis gives a retiring employees with title wise breakdown, Pewlett Hackard may need to fill in the below roles.
| Title | Retiring Employees |
| ------ | ------ |
| Senior Engineer | 25916 |
| Senior Staff | 24926 |
| Engineer | 9285 |
| Staff | 7636 |
| Technique Leader | 3603 |
| Assistant Engineer | 1090 |
| Manager | 2 |
