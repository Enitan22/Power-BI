# Power-BI
PALMORA HR GROUP
# DSA POWER BI PROJECT
## Palmora Group HR Analysis
### Analysis of gender distribution, rating, and inequality in Palmora Group's workforce, exploring trends and insights across departments and regions.

## Objective

### Analyse Palmora Group workforce to generate insights using charts,tables,graphs and calculated columns.

## Project Context
Client Name: CHRO, Mr Yunus Shofoluwe

Industry: Manufacturing

Role: HR Analyst

Tools Used: Power BI (Charts, Cards, Conditional Formatting, Custom Formatting)

## Dataset Description
* Total Records: 1016
* Columns: 6
* Fields Included:
   * Employee Name
   * Gender
   * Department
   * Salary
   * Region
   * Rating

## Key Analytical Tasks & Solutions
| Task Description | Power BI Tools/Logic Used |
| ---------------- | ------------------------- |
| 1  What is the gender distribution in the organization? Distill to regions and departments | Clustered column chart , donut chart and average formula |
| 2  Assign a generic gender status to employees who refused to disclose their gender | Categorized as other |
| 3  Take out the employees that are no longer with the company | Removed empty rows
| 4  Take out some departments indicated as NULL | Filtered and unchecked NULL |
| 5  Show insights on ratings based on gender | Stacked column chart |
| 6  Analyse the company's salary structure | Matrix, piechart |
| 7  Does Palmora meet the criteria to pay minimum of $90,000 to employees | DAX measure, pie chart |
| 8  Bonus paid to individual employees | Custom column (salary * bonus ), stacked column chart |
| 9  Total amount paid to individual employees (salary inclusive of bonus ) | Custom column (salary * bonus) + salary, stacked column chart |
| 10 Total amount paid out per region and company | Card (bonus plus salary), stacked column chart |

## Business Insights (Summary)
Management should encourage staff to reveal their gender for proper accountability considering the fact that the media already holds a notion that the organization is gender biased.
