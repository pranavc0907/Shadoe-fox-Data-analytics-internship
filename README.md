# ShadowFox Data Analyst Internship

**Intern:** Pranav | **Role:** Data Analyst | **Track:** Beginner → Intermediate → Advanced

This repository contains all three levels of the ShadowFox Data Analyst
internship task list. Each level uses a different dataset and a different
tool, chosen deliberately to show progression — spreadsheet fundamentals →
Python-based analysis → interactive BI dashboarding — while answering the
same underlying question at increasing depth: what's happening in the
business, why, and what should be done about it.

## Quick Links
| Level | Folder | Dataset | Tool |
|---|---|---|---|
| 🟢 Beginner | [`beginner-superstore/`](./beginner-superstore/) | Sample Superstore | Excel |
| 🟡 Intermediate | [`Intermediate_sample-superstore/`](./Intermediate_sample-superstore/) | Full Superstore Workbook | Python + Excel |
| 🔴 Advanced | [`Advanced-level HR Workforce & Attrition Dashboard/`](./Advanced-level%20HR%20Workforce%20%26%20Attrition%20Dashboard/) | IBM HR Analytics | Power BI |

*(If any of these folder names don't match your actual repo exactly, adjust the links above to fit — GitHub links are case- and space-sensitive.)*

---

## 🟢 Beginner — Sample Superstore Sales & Profit Dashboard
A spreadsheet-based dashboard analyzing retail sales and profit across
categories, sub-categories, regions, and customer segments.
- **Dataset:** Sample Superstore (Kaggle, simplified cut) — 9,994 orders
- **Tool:** Excel — `SUMIFS`, `COUNTIFS`, KPI cards, native charts
- **Headline finding:** discounts above ~20% turn orders unprofitable; the
  Tables sub-category alone loses $17.7K, dragging down all of Furniture.
- **Full details:** see `Readme.md` inside the folder

## 🟡 Intermediate — Customer & Revenue Performance Analysis
Customer-level and time-based analysis on a richer version of the same
retail business — revenue concentration, repeat purchase behaviour, cohort
retention, seasonality, and returns.
- **Dataset:** Full Sample Superstore workbook — 793 customers, 5,009
  orders, 2014–2017
- **Tools:** Python (pandas + matplotlib) **and** Excel — the same analysis
  built in both, to show range
- **Headline finding:** the West region is the most profitable by margin,
  but has a return rate ~3x every other region — a quality issue hiding
  underneath strong headline numbers.
- **Full details:** see `Readme.md` inside the folder

## 🔴 Advanced — HR Workforce & Attrition Executive Dashboard
An interactive Power BI dashboard analyzing employee attrition, built for
an executive audience with KPI cards, filterable charts, and a slicer.
- **Dataset:** IBM HR Analytics Employee Attrition & Performance (Kaggle) —
  1,470 employees
- **Tool:** Power BI — DAX measures, bar/donut charts, Department slicer
- **Headline finding:** employees working overtime leave at ~3x the rate of
  those who don't (30.5% vs 10.4%), and Sales Executives have the highest
  attrition of any role (39.8%).
- **Full details:** see `Readme.md` inside the folder

---

## Skills Demonstrated by Level
| Level | Tool | Core Skills |
|---|---|---|
| Beginner | Excel | Data cleaning, SUMIFS/COUNTIFS, pivot-style summary tables, charting, business interpretation |
| Intermediate | Python (pandas) + Excel | Customer-level analysis, cohort/retention logic, revenue concentration (Pareto), time-series trends, dual-tool delivery |
| Advanced | Power BI | DAX measures, interactive filtering, executive dashboard design, decision-oriented insight presentation |

## Repository Structure
```
shadowfox-data-analyst-internship/
├── README.md                                          ← you are here
├── beginner-superstore/
│   ├── Readme.md
│   ├── SampleSuperstore.xlsx
│   └── Superstore_Beginner_Dashboard.xlsx
├── Intermediate_sample-superstore/
│   ├── Readme.md
│   ├── SampleSuperstore (2).xlsx
│   ├── Superstore_Intermediate_Dashboard.xlsx
│   └── intermediate_analysis.ipynb
└── Advanced-level HR Workforce & Attrition Dashboard/
    ├── Readme.md
    ├── HR Workforce & Attrition Executive Dashboard.pbix
    └── HR_Attrition_Cleaned.csv
```

## How to View Each Deliverable
- **`.xlsx` files** — open in Excel, Google Sheets, or LibreOffice Calc.
  All KPIs and tables are live formulas.
- **`.ipynb`** — open in Jupyter, VS Code, or Google Colab. Already
  executed, so charts and outputs render without rerunning anything.
- **`.pbix`** — requires Power BI Desktop (free, Windows only).

## Tools Used Across the Internship
Excel (formulas, PivotTables, charts) · Python (pandas, matplotlib,
Jupyter) · Power BI (DAX, interactive dashboards)

## Acknowledgement
I would like to thank ShadowFox for the opportunity to complete this Data
Analyst internship, and my coordinator for guidance throughout. All tasks
were completed independently, using the datasets and tools appropriate to
each level as outlined in the internship task list.

## Submission Notes
Per the internship's submission process, this repository is the required
GitHub submission
