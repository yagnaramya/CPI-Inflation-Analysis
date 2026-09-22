# India CPI Inflation Analysis & Dashboard

## Project Overview

This project analyzes India's Consumer Price Index (CPI) data using Microsoft Excel to identify inflation trends, category-level contributions, food inflation movements, and changes around the COVID-19 period.
The analysis was performed using Advanced Excel techniques including data cleaning, missing-value treatment, data transformation, PivotTables, percentage calculations, and data visualization.

---

## Business Objective

The objective of this analysis is to understand how India's CPI changed over time and identify the major categories and periods contributing to inflation.
The analysis focuses on four key areas:
1. Contribution of broader CPI categories to the overall basket
2. Year-over-year (YoY) CPI inflation trends
3. Food inflation trends and category-level changes
4. Impact of the COVID-19 period on CPI inflation

---

## Dataset

The dataset contains CPI index values extracted from Government of India CPI data.
The data includes:
- Rural CPI
- Urban CPI
- Rural + Urban (Combined) CPI
- Multiple CPI categories and sub-categories
- Monthly observations across multiple years
CPI is an index used to measure changes in the general level of prices over time. It is not a direct measure of individual product prices.

---

## Tools & Technologies

- Microsoft Excel
- Advanced Excel
- PivotTables
- Data Cleaning
- Data Transformation
- Percentage Change Analysis
- Linear Interpolation
- Data Visualization

---

## Data Preparation

The dataset contained missing values that required treatment before analysis.

### Missing Value Treatment

Missing observations were handled using **linear interpolation** between available observations where appropriate.
The cleaned dataset was then transformed into an analysis-friendly structure using an unpivoting approach.

### Data Transformation

The original data was converted from a wide format into a more analysis-friendly structure containing fields such as:
- Year
- Month
- Sector
- Category
- CPI Index
This structure enabled category-level analysis using PivotTables.

---

## Analysis Performed

### 1. CPI Category Contribution

Similar CPI categories were grouped into broader analytical buckets to understand their contribution to the overall CPI basket.
The contribution percentages were calculated so that the combined contribution of the broader categories represents 100%.
This analysis helps identify which broad areas of consumer expenditure have the largest representation in the CPI basket.

---

### 2. Year-over-Year CPI Inflation Trend

The Rural + Urban General Index was used to analyze annual YoY inflation.
The YoY percentage change was calculated using an Excel PivotTable with:
**Show Values As → % Difference From → Previous**

| Year | YoY Inflation |
|------|---------------|
| 2017 | 3.33% |
| 2018 | 3.95% |
| 2019 | 3.90% |
| 2020 | 6.01% |
| 2021 | 5.63% |
| 2022 | 6.62% |
| 2023* | 3.18% |

**Key observation:** The highest observed annual YoY inflation rate in the analyzed period was **6.62% in 2022**.
\*2023 represents a partial period based on the available dataset and should not be interpreted as a full-year inflation rate.

---

### 3. Food Inflation Analysis

The food category was analyzed over the 12-month period ending May 2023.
The analysis includes:
- Monthly food inflation movements
- Month-on-month changes
- Highest and lowest food inflation periods
- Absolute changes across individual food categories
- Identification of categories showing larger changes within the broader food basket
This analysis helps understand which food-related categories experienced the largest movements during the selected period.

---

### 4. COVID-19 Impact Analysis

The analysis examines CPI movements around the COVID-19 period, using **March 2020 as the reference point for the onset of the pandemic period**.
The analysis compares inflation trends before and after this period, with particular attention to categories related to:
- Food
- Healthcare
- Essential goods and services
The objective is to identify changes in inflation patterns around the COVID-19 period rather than attribute individual price movements solely to the pandemic.

---

## Dashboard

The Excel dashboard brings together the major findings from the analysis, including:
- CPI inflation trends
- Category contribution
- Food inflation movements
- COVID-19 period analysis
The dashboard provides a consolidated view of the analysis for easier interpretation of the major trends.

---

## Project Structure

```text
CPI-Inflation-Analysis/
│
├── CPI_Inflation_Analysis_Dashboard.xlsx
│
└── README.md
