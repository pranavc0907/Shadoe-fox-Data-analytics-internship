# Advanced Level — HR Workforce & Attrition Executive Dashboard

**ShadowFox Data Analyst Internship — Level 3 (Advanced)**

## Overview
An interactive executive dashboard built in Power BI analyzing employee
attrition at a fictional company, using the IBM HR Analytics Employee
Attrition & Performance dataset. The dashboard surfaces where attrition is
concentrated (department, job role) and what's driving it (overtime,
business travel, gender split), with a filterable view rather than a static
chart collection.

## Dataset
- **Source:** IBM HR Analytics Employee Attrition & Performance (Kaggle)
- **File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Size:** 1,470 employees, 35 original columns
- **Fields used:** Age, Attrition, BusinessTravel, Department, Gender,
  JobRole, MonthlyIncome, OverTime, and other employee attributes

## Data Cleaning
- Verified 0 missing values, 0 duplicate rows
- Dropped 3 constant columns with no analytical value: `EmployeeCount`,
  `Over18`, `StandardHours`
- Added derived `AgeBucket` and `TenureBucket` columns for cleaner grouping
  in visuals

## Dashboard Structure
**KPI Cards**
- Total Headcount: 1,470
- Total Attrition: 237
- Attrition Rate: 16.12%

**Visuals**
- Attrition Count by Department (bar chart)
- Employee Count by Job Role, split by Attrition (bar chart)
- Attrition Count by OverTime (bar chart)
- Attrition share by Gender (donut chart)
- Attrition by Business Travel frequency (bar chart)

**Interactivity**
- Department slicer — filters every visual on the page by department
  (Human Resources / Research & Development / Sales)

## Key Findings
- Overall attrition rate is **16.12%** (237 of 1,470 employees).
- **OverTime is the strongest single driver**: employees working overtime
  leave at roughly 3x the rate of those who don't (30.5% vs 10.4%).
- **Sales Executive** has the highest job-role attrition rate in the
  dataset (39.8%), far above roles like Research Director (2.5%).
- **Frequent travelers** leave at 24.9%, more than 3x the rate of employees
  who don't travel for work (8.0%).
- Attrition skews toward **younger, newer employees** — the 18-25 age
  bracket and employees with 0-1 years of tenure both show attrition rates
  above 30%, compared to under 10% for tenured/older employees.

## Recommendations
1. Review overtime policy and workload distribution — it's the single
   clearest attrition signal in the data.
2. Investigate the Sales Executive role specifically (compensation
   structure, manager support, or role expectations) given its outsized
   attrition rate relative to every other role.
3. Reassess frequent-travel assignments, or add support/compensation for
   employees who travel often.
4. Strengthen onboarding and early-tenure engagement, since attrition is
   heavily concentrated in an employee's first year.

## Tools Used
Power BI Desktop (DAX measures: `Total Employees`, `Attrition Count`,
`Attrition Rate %`; bar, donut, and slicer visuals)

## Files
- # Advanced Level — HR Workforce & Attrition Executive Dashboard

**ShadowFox Data Analyst Internship — Level 3 (Advanced)**

## Overview
An interactive executive dashboard built in Power BI analyzing employee
attrition at a fictional company, using the IBM HR Analytics Employee
Attrition & Performance dataset. The dashboard surfaces where attrition is
concentrated (department, job role) and what's driving it (overtime,
business travel, gender split), with a filterable view rather than a static
chart collection.

## Dataset
- **Source:** IBM HR Analytics Employee Attrition & Performance (Kaggle)
- **File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Size:** 1,470 employees, 35 original columns
- **Fields used:** Age, Attrition, BusinessTravel, Department, Gender,
  JobRole, MonthlyIncome, OverTime, and other employee attributes

## Data Cleaning
- Verified 0 missing values, 0 duplicate rows
- Dropped 3 constant columns with no analytical value: `EmployeeCount`,
  `Over18`, `StandardHours`
- Added derived `AgeBucket` and `TenureBucket` columns for cleaner grouping
  in visuals

## Dashboard Structure
**KPI Cards**
- Total Headcount: 1,470
- Total Attrition: 237
- Attrition Rate: 16.12%

**Visuals**
- Attrition Count by Department (bar chart)
- Employee Count by Job Role, split by Attrition (bar chart)
- Attrition Count by OverTime (bar chart)
- Attrition share by Gender (donut chart)
- Attrition by Business Travel frequency (bar chart)

**Interactivity**
- Department slicer — filters every visual on the page by department
  (Human Resources / Research & Development / Sales)

## Key Findings
- Overall attrition rate is **16.12%** (237 of 1,470 employees).
- **OverTime is the strongest single driver**: employees working overtime
  leave at roughly 3x the rate of those who don't (30.5% vs 10.4%).
- **Sales Executive** has the highest job-role attrition rate in the
  dataset (39.8%), far above roles like Research Director (2.5%).
- **Frequent travelers** leave at 24.9%, more than 3x the rate of employees
  who don't travel for work (8.0%).
- Attrition skews toward **younger, newer employees** — the 18-25 age
  bracket and employees with 0-1 years of tenure both show attrition rates
  above 30%, compared to under 10% for tenured/older employees.

## Recommendations
1. Review overtime policy and workload distribution — it's the single
   clearest attrition signal in the data.
2. Investigate the Sales Executive role specifically (compensation
   structure, manager support, or role expectations) given its outsized
   attrition rate relative to every other role.
3. Reassess frequent-travel assignments, or add support/compensation for
   employees who travel often.
4. Strengthen onboarding and early-tenure engagement, since attrition is
   heavily concentrated in an employee's first year.

## Tools Used
Power BI Desktop (DAX measures: `Total Employees`, `Attrition Count`,
`Attrition Rate %`; bar, donut, and slicer visuals)

## Files
- `# Advanced Level — HR Workforce & Attrition Executive Dashboard

**ShadowFox Data Analyst Internship — Level 3 (Advanced)**

## Overview
An interactive executive dashboard built in Power BI analyzing employee
attrition at a fictional company, using the IBM HR Analytics Employee
Attrition & Performance dataset. The dashboard surfaces where attrition is
concentrated (department, job role) and what's driving it (overtime,
business travel, gender split), with a filterable view rather than a static
chart collection.

## Dataset
- **Source:** IBM HR Analytics Employee Attrition & Performance (Kaggle)
- **File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- **Size:** 1,470 employees, 35 original columns
- **Fields used:** Age, Attrition, BusinessTravel, Department, Gender,
  JobRole, MonthlyIncome, OverTime, and other employee attributes

## Data Cleaning
- Verified 0 missing values, 0 duplicate rows
- Dropped 3 constant columns with no analytical value: `EmployeeCount`,
  `Over18`, `StandardHours`
- Added derived `AgeBucket` and `TenureBucket` columns for cleaner grouping
  in visuals

## Dashboard Structure
**KPI Cards**
- Total Headcount: 1,470
- Total Attrition: 237
- Attrition Rate: 16.12%

**Visuals**
- Attrition Count by Department (bar chart)
- Employee Count by Job Role, split by Attrition (bar chart)
- Attrition Count by OverTime (bar chart)
- Attrition share by Gender (donut chart)
- Attrition by Business Travel frequency (bar chart)

**Interactivity**
- Department slicer — filters every visual on the page by department
  (Human Resources / Research & Development / Sales)

## Key Findings
- Overall attrition rate is **16.12%** (237 of 1,470 employees).
- **OverTime is the strongest single driver**: employees working overtime
  leave at roughly 3x the rate of those who don't (30.5% vs 10.4%).
- **Sales Executive** has the highest job-role attrition rate in the
  dataset (39.8%), far above roles like Research Director (2.5%).
- **Frequent travelers** leave at 24.9%, more than 3x the rate of employees
  who don't travel for work (8.0%).
- Attrition skews toward **younger, newer employees** — the 18-25 age
  bracket and employees with 0-1 years of tenure both show attrition rates
  above 30%, compared to under 10% for tenured/older employees.

## Recommendations
1. Review overtime policy and workload distribution — it's the single
   clearest attrition signal in the data.
2. Investigate the Sales Executive role specifically (compensation
   structure, manager support, or role expectations) given its outsized
   attrition rate relative to every other role.
3. Reassess frequent-travel assignments, or add support/compensation for
   employees who travel often.
4. Strengthen onboarding and early-tenure engagement, since attrition is
   heavily concentrated in an employee's first year.

## Tools Used
Power BI Desktop (DAX measures: `Total Employees`, `Attrition Count`,
`Attrition Rate %`; bar, donut, and slicer visuals)

## Files
- `HR Workforce & Attrition Executive Dashboard.pbix` — the Power BI dashboard file.
- `HR_Attrition_Cleaned.csv` — cleaned source data.
