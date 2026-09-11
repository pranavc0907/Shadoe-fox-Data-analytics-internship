# Intermediate Level — Customer & Revenue Performance Analysis

**ShadowFox Data Analyst Internship — Level 2 (Intermediate)**

## Overview
This project moves beyond the Beginner-level summary dashboard into
customer-level and time-based analysis: revenue concentration, repeat
purchase behaviour, acquisition-cohort retention, seasonality, and a
returns-driven quality signal — each paired with a business recommendation,
not just a description of the numbers.

The analysis was built twice, deliberately, in two different tools:
- A **Python notebook** to show the analytical process step by step
- An **Excel dashboard** as the polished, business-facing deliverable

The brief for this level didn't specify a tool, so both are included to show
range rather than picking one arbitrarily.

## Dataset
- **Source:** Full Sample Superstore workbook (`SampleSuperstore__2_.xlsx`)
- **Sheets used:** Orders (9,994 rows / 21 columns), Returns (296 rows)
- **Fields:** Order Date, Ship Date, Customer ID, Customer Name, Product
  Name, Category, Sub-Category, Region, Segment, Sales, Quantity, Discount,
  Profit
- This is a richer file than the Beginner dataset — it adds real dates and
  customer identifiers, which is what makes customer-level and time-based
  analysis possible at this level.

## Data Cleaning
- Verified 0 duplicate rows and 0 missing values across all columns
- Converted Order Date / Ship Date to proper datetime types
- Derived Year, Quarter, and Year-Month fields for trend analysis
- Joined a `Is Returned` flag from the Returns sheet onto every order line
- (Excel version) added a `FirstLineOfOrder` helper column using an
  expanding `COUNTIF` to enable distinct order/customer counts, since plain
  SUMIFS/COUNTIFS count rows, not unique values

## Approach
| Analysis area | What it shows |
|---|---|
| Seasonality | Monthly/quarterly sales trend across 2014-2017 |
| Revenue concentration | Pareto curve — what % of customers drive 80% of revenue |
| Repeat purchase behaviour | % of customers who buy more than once |
| Cohort retention | % of each acquisition-year cohort still active in later years |
| Returns analysis | Return rate by region and category (churn-adjacent signal) |
| Top customers | Highest-revenue accounts by name |

## Key Metrics
- Total Sales: **$2,297,201** | Total Profit: **$286,397**
- Overall Profit Margin: **12.5%**
- Unique Customers: **793** | Unique Orders: **5,009**
- Avg Orders per Customer: **6.3**

## Key Findings
- **Seasonality:** sales climb steadily every year and peak in Q4
  (November especially) — a recurring pattern, not a one-off spike.
- **Revenue concentration:** moderately concentrated — the top 20% of
  customers (158 of 793) generate 48% of revenue, and it takes ~50% of the
  customer base to reach 80% of revenue.
- **Repeat purchase:** 98.5% of customers are repeat buyers, averaging 6.3
  orders each — this is fundamentally a repeat-purchase business.
- **Cohort retention:** every cohort dips in year two (e.g. 2014 cohort
  fell to 73% active in 2015) but recovers to 85%+ active by its most
  recent year.
- **Returns — the standout finding:** the **West region** has a return
  rate ~3x every other region (~15.3% vs 4-5% elsewhere), despite being the
  *most profitable* region by margin. Category-level return rates are much
  more even (~8% across all categories), pointing to a regional
  operations/fulfillment issue rather than a product-line one.

## Recommendations
1. Plan inventory, staffing, and marketing spend around the recurring Q4
   demand spike.
2. Build a top-accounts watchlist for the highest-revenue customers.
3. Focus retention on growing basket size per repeat customer, since
   one-time buyers are already a small minority.
4. Investigate the year-2 retention dip with a targeted second-year
   touchpoint.
5. Audit West region fulfillment/product quality — strong headline numbers
   there may be masking an issue that could erode margin as the region
   grows.

## Tools Used
- **Python:** pandas, matplotlib (in `intermediate_analysis.ipynb`)
- **Excel:** SUMIFS, COUNTIFS, SUMPRODUCT, expanding-range COUNTIF (in
  `Superstore_Intermediate_Dashboard.xlsx`)

## Files
- `intermediate_analysis.ipynb` — full Python analysis notebook (code,
  charts, and markdown explanations)
- `Superstore_Intermediate_Dashboard.xlsx` — Excel dashboard version
  (7 tabs: Raw Data, Summary Dashboard, Monthly Trend, Customer Summary,
  Returns Analysis, Retention Cohort, Insights & Recommendations)
- `data/SampleSuperstore__2_.xlsx` — source data
