# ABC Company Employee Data Analysis

## Overview:
This project analyzes employee data from ABC Company, which consists of 458 rows and 9 columns. The objective is to preprocess the data, perform specific analyses on employee distribution, salary, and age groups, and visualize key insights to provide a comprehensive understanding of employee demographics and expenses across teams and positions.

## Dataset Information
The dataset provided by ABC Company includes the following columns:
1. **Employee Name** - Name of each employee
2. **Number** - Number of each player which is not unique
3. **Team** - The team each employee belongs to
4. **Position** - The employee’s position within the team
5. **Age** - The age of each employee
6. **Height** - The height of each employee (to be replaced with consistent random data)
7. **Weight** - The weight of each employee
8. **College** - The college which each employee belongs to
9. **Salary** - Annual salary of each employee

# PREPROCESSING:
1.Height Column Replacement: The original "Height" column contained inconsistent values.To standardize this,I replaced it with random heights between the values 150 cm and 180 cm.

2.Data Consistency Checks: Ensured all columns contain consistent data types and handle any missing values appropriately.

# Data Analysis:
1.Employee Distribution by Team: Calculate the number of employees in each team and their percentage of the total workforce.
2.Position Segregation: Group employees based on their positions and calculate the count for each position.
3.Predominant Age Group: Identify the most common age group by creating age bins.
4.Highest Salary Expenditure by Team and Position: Group data by "Team" and "Position" to find which combinations have the highest salary totals.
5.Correlation Analysis: Calculate and visualize the correlation between employee age and salary.

