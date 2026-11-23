# Retail Business Analytics

## Project Overview

This project demonstrates an end-to-end business analytics workflow, covering data preparation, exploratory data analysis, data visualisation, and business intelligence reporting.

The project is divided into three parts, each focusing on a different stage of the analytical process. Python is used for data cleaning and visual analysis, while Power BI is used to develop a business analytics report.

## Project Objectives

1. Prepare and clean a dataset by identifying and addressing data quality issues.
2. Explore business performance using descriptive statistics and data visualisations.
3. Identify key business trends, patterns, and performance differences.
4. Translate analytical findings into actionable business recommendations.
5. Develop a Power BI report to support business analysis and data-driven decision-making.

## Project Structure

```text
retail-business-analytics/
│
├── part-1-data-cleaning/
│   ├── data/
│   ├── data_cleaning_preparation.ipynb
│   └── retail_matcha_sales_cleaned.xlsx
│
├── part-2-data-visualisation/
│   ├── data/
│   ├── data_visualisation.ipynb
│   └── analysis_report.pdf
│
├── part-3-power-bi/
│   └── business_analytics_case_study.pbix
│
├── README.md
└── .gitignore
```

## Part 1 – Data Cleaning and Preparation

**Tools:** Python, Pandas, NumPy, Jupyter Notebook

The first part focuses on preparing a deliberately messy retail sales dataset for further analysis.

The dataset contains fictional retail matcha transactions and was synthetically generated for educational purposes. It includes intentionally introduced data quality issues.

Key activities:

- Dataset exploration and structural assessment.
- Identification and treatment of missing values.
- Duplicate record detection and removal.
- Standardisation of inconsistent categorical values.
- Correction of incorrectly formatted numerical values.
- Data type conversion and validation.
- Export of the cleaned dataset.

## Part 2 – Data Visualisation and Insights

**Tools:** Python, Pandas, Matplotlib, Seaborn

The second part explores retail sales performance using a dataset containing 384 transactions across four geographical regions and four product categories during 2025.

Five visualisations were developed:

1. Monthly Revenue Over Time.
2. Revenue by Region.
3. Revenue by Product Category.
4. Distribution of Revenue.
5. Revenue Distribution by Product Category.

### Key Findings

- Monthly revenue increased by approximately 33% between January and December 2025.
- The West region generated the highest total revenue, while the North recorded the lowest.
- Electronics was the strongest revenue-generating product category.
- Clothing had the lowest median revenue per order.
- Revenue distribution was positively skewed, indicating the presence of higher-value transactions.

### Business Recommendations

1. Improve Clothing category performance through targeted promotions, product bundling, and cross-selling.
2. Investigate regional performance differences and use revenue trends to support inventory and staffing decisions.

The analysis covers one year only, so the observed revenue increase should not be interpreted as evidence of recurring seasonal growth. Revenue also does not represent profit.

## Part 3 – Power BI Business Analytics

**Tool:** Microsoft Power BI

The final part focuses on business analytics and reporting using Power BI.

The deliverable is an interactive Power BI report (`.pbix`) developed as part of the Business Analytics Case Study.

The report provides a business intelligence component to complement the Python-based data preparation and visual analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI
- Excel

## Limitations

- The matcha retail dataset in Part 1 is synthetically generated and does not represent actual business transactions.
- The visual analysis in Part 2 covers transactions from 2025 only.
- Revenue-based findings do not account for product margins, operating costs, or profitability.
- Business recommendations should be validated against additional operational and financial data.

## Purpose

This project was completed as part of postgraduate studies in Business Analytics. It demonstrates practical skills in data preparation, exploratory analysis, visualisation, business interpretation, and business intelligence reporting.
