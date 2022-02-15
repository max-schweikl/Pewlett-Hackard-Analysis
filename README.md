# Pewlett-Hackard-Analysis

## Overview

The purpose of this analysis is to understand how many employees are retiring by title in the upcoming "Silver Tsunami."  Of those employees, we'd also like to understand which would be eligible for the upcoming mentorship program.  The analysis will show all potentially impacted "future retiree" employees that were born between 1/1/1952 and 12/31/1955 as well as eliglble employees for the mentorship program that were born between 1/1/1965 and 12/31/1965

## Results

### Retirement-Eligible Employee List
- By forming the retirement_titles table, we were able to determine all employees eligible for retirement and how long they worked at each Pewlett-Hackard position over the course of their career.

### Retirement-Eligible Employees by Most-Recent Role
- Since some employees may have worked multiple positions at Pewlett-Hackard, the unique_titles table was created to show the eligible employees, but just what their most recent title is at retirement age.

### Retirement-Eligible Employees by Position Title
- To understand how many retiring employees are in each title, we created the retiring_titles table, which showed that a large majority of employees (roughly xx%) had a senior level position at time of retirement.

### Mentorship-Eligible Employee List
- Finally, to understand employees that are eligible for mentorship eligibility, this required joining together tables across our analysis to see their title as well.  Just from an intial glance, we can see that most of the employees here hold senior titles (not surprising considering the majority of employees nearing retirement hold senior level role titles).

## Summary

Currently, Pewlett-Hackard has nearly 73k employees of it's employment nearing retirement or towards a mentorship program.  To get a better idea of the retirement impact total by department, you can access the retirement_titles table as this will have all the necessary information, only one additional step would be to run a query of staff count total that will retire by department, to better understand where roles will need to be filled.  To understand if there will be enough qualified staff to train the next generation of employees, you can expand on the titles table to only look at senior positions to understand how many qualified employees are in each department to assist as mentors for the next working generation.  Ideally, the ratio should be no more than 1:3 (1 senior level employee for every 3 entry level employees) to ensure the most optimal mentorship experience.

