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
|S/N |Task Description | Power BI Tools/Logic Used | Insight | 
|---- |---------------- | ------------------------- | -----------|
| 1| What is the gender distribution in the organization? Distill to regions and departments | Data transformation, Clustered Column chart and Data Filters|There are generally more Male staff than Female NB: Exemption of those that didn't reveal their egender|
| 2| Assign a generic gender status to employees who refused to disclose their gender | On the Gender Column Replace values was used | "Other" was used as assigned generic gender|
| 3| Take out the employees that are no longer with the company | Removed empty rows| 946 data-rows was left|
| 4| Take out some departments indicated as NULL | Replace values that is Null with Empty, Remove Empty | 946 data-rows was left | 
| 5| Show insights on ratings based on gender | Clustered column chart | The male has the highest number of poor Performance while the female has the highest number of Good performance|
| 6| Company's salary structure based on gender pay Gap| Average of Salary by Gender using treeMap, Matrix For Min Salary and Donut for Sum of salary| There is a salary Pay gap based on gender therefore, the following departs and regions needs improvement Departments and region that needs improvement: 1. Human resources-Lagos 2. Accounting- Kaduna 3. Research and Development-LAgos 4.  Research and Development-Abuja 5. Business Development-Abuja6. Legal-Abuja 7. Engineering-Abuja|
| 7| Does Palmora meet the criteria to pay minimum of $90,000 to employees | Conditional column, and card | No because out of the 946 employees only 292 earns above 90,000|
| 8| Bonus paid to individual employees | Data Import, Unpivot, Merge queries, Rename| A handful of bonus was paid based on their performane rating in which the highest sum of salary went to KADUNA||
| 9| Total amount paid to individual employees (salary inclusive of bonus ) | Custom column (salary * bonus) + salary, stacked column chart | Their is an obvious increase in salary|
|10| Total amount paid out per region and company | Clustered column chart | Kaduna has the the highest. In the this order: Kaduna>Abuja>Lagos. Lagos Employee has a very Low performance| 

## Business Insights (Summary)
1. Management should encourage staff to reveal their gender for proper accountability considering the fact that the media already holds a notion that the organization is gender biased.
2. Lagos Region poor performance may be due to living Condition in Lagos that is the management can provide a good welfare package for their ALgos employee to increasee performance of the staff and yield more profit
3. Palmora should increase the salary of their staffs in order to meet the generally accepted standard.
