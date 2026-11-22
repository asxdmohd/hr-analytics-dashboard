# HR Analytics – Employee Attrition Dashboard (Power BI)

An interactive one-page Power BI dashboard that explores **why employees leave** a company. It breaks attrition down by department, age, job role, salary, education, gender and tenure.

## Dataset

`HR_Analytics.csv` has 1,480 employee records and 38 columns. They cover demographics, job role, department, salary slab, satisfaction scores, overtime and tenure.

**Data cleaning in Power Query:** removed duplicate records and rows with missing values (in `YearsWithCurrManager`), which leaves about 1,413 employees.

## Dashboard

- **KPI cards:** Employee Count, Attrition Count, Attrition Rate, Average Age, Average Monthly Salary and Average Years at Company
- **Department slicer** that filters the whole page
- **Attrition by age group** (column chart)
- **Attrition by salary slab** (bar chart)
- **Attrition by job role** (bar chart)
- **Attrition by education field** (donut chart)
- **Attrition by gender** (treemap)
- **Attrition by years at company** (line chart)
- **Job role × job satisfaction** (matrix)

## Key insights

- **229 of about 1,413 employees left, an attrition rate of 16.2%.** The average employee is about 37 years old, earns about 6.5K a month and has been with the company for 7 years.
- **Young employees leave most often.** The 18–25 group has an attrition rate of about 37%, against about 9% for 36–45. In absolute numbers, the 26–35 group loses the most people (111).
- **Low pay is the clearest driver.** Employees earning up to 5K a month leave at 22%, compared with under 4% for those earning above 15K. This group accounts for about 69% of everyone who left.
- **Sales Representatives have the highest turnover** at about 40%, followed by Laboratory Technicians and HR staff at about 24% each. Managers and Research Directors stay the longest (under 5%).
- **By department, Sales (21%) and HR (19%) lose people faster than R&D (14%).**

## Skills demonstrated

Data cleaning in Power Query · Data modelling · DAX measures (attrition count and rate) · Interactive filtering with slicers · KPI design · Custom report theming

## How to open

1. Download `HR ANALYTICS.pbix`.
2. Open it in Power BI Desktop (free).
3. If prompted, point the data source to `HR_Analytics.csv`.

## Tools

Power BI Desktop · Power Query · DAX
