# PhonePe Payment Insights Dashboard

## Project Overview

The **PhonePe Payment Insights Dashboard** is an interactive data visualization project designed to present payment transaction performance, user activity, and transaction trends in a clear and business-friendly format.

The dashboard provides a high-level view of key payment metrics and allows users to explore transaction status, monthly trends, age-segment contribution, service-wise transaction value, top users, and weekday versus weekend usage.

> **Note:** The metrics shown in the dashboard image are displayed as visual examples. Replace them with verified values from your dataset before using them in a formal report or presentation.

## Dashboard Preview

Add your dashboard screenshot to this repository and update the image path below if needed.

![PhonePe Payment Insights Dashboard](dashboard.png)

## Objectives

- Monitor overall transaction volume and transaction value.
- Review transaction status across successful, pending, and failed payments.
- Track transaction trends over time.
- Understand user and age-segment contribution.
- Compare transaction value across service categories.
- Identify top users by transaction value.
- Compare weekday and weekend usage.
- Present actionable insights through a single dashboard.

## Key Performance Indicators (KPIs)

- **Total Transactions:** Overall number of payment transactions.
- **Total Value:** Total monetary value of transactions.
- **Unique Users:** Number or share of distinct users represented in the data.
- **Successful Rate:** Success rate of payment transactions.
- **Month-over-Month (MoM) Growth:** Change in a metric compared with the previous month.

*Confirm the definitions and calculation formulas for each KPI against your data model.*

## Dashboard Features

### 1. Filters
- Month selector
- Payment status categories: Failed, Pending, and Successful

### 2. Transactions Over Time
A monthly trend chart compares transaction volume and transaction value to help identify peaks, dips, and changes over the year.

### 3. Age Segment Contribution
A doughnut chart shows the contribution of age groups to the selected measure.

### 4. Service Transaction Value Analysis
A horizontal bar chart compares transaction value across service categories, such as:
- Loans
- Insurance
- Money Transfer
- Recharge Bills

### 5. Top 5 Users
A bar chart ranks the top five users by transaction value.

### 6. Weekday vs. Weekend Usage
A doughnut chart compares activity during weekdays and weekends.

### 7. Insights Panel
A dedicated panel highlights an observation from the dashboard. For example, the displayed dashboard notes higher transaction activity on weekdays. Validate this observation against the underlying dataset before reporting it as a conclusion.

## Tools and Technologies

Update this section to reflect the tools you actually used.

- **Power BI** — dashboard creation and data visualization, if used
- **Power Query** — data cleaning and transformation, if used
- **DAX** — KPI and measure calculations, if used
- **Excel / CSV / SQL** — possible data sources or preparation tools, if used

## Dataset

The dashboard screenshot does not specify the source dataset. Add the following details when available:

- Dataset name and source
- Time period covered
- Number of records
- Important columns, such as transaction ID, transaction date, transaction amount, payment status, user ID, age segment, and service category
- Data cleaning and validation steps
- Any limitations or assumptions

Do not include private, sensitive, or identifiable customer information in the repository.

## Workflow

1. **Collect data:** Import the PhonePe-related transaction dataset.
2. **Clean data:** Handle missing values, duplicates, inconsistent categories, and incorrect data types.
3. **Prepare metrics:** Define transaction counts, transaction value, success rate, unique users, and month-over-month growth.
4. **Build visuals:** Create KPI cards, trend charts, contribution charts, category comparisons, and user rankings.
5. **Add filters:** Enable month and payment-status filtering where supported.
6. **Validate results:** Compare dashboard totals and calculations with the source data.
7. **Present insights:** Summarize trends and potential areas for further investigation.

## Business Questions

This dashboard can help explore questions such as:

- How do transaction volume and value change month by month?
- What proportion of transactions are successful, pending, or failed?
- Which age segments contribute the most to activity?
- Which service categories have the highest transaction value?
- Which users have the highest transaction value?
- Is activity different on weekdays and weekends?
- Are there unusual changes that require further investigation?

## Key Insights

Record your verified findings here after checking the underlying data. Possible areas to investigate include:

- Months with the highest and lowest transaction volume
- Changes in payment success and failure rates
- Service categories contributing the most transaction value
- Differences between weekday and weekend activity
- Concentration of transaction value among the top users

Avoid treating the illustrative values or observations in the screenshot as verified business findings.

## How to View the Project

1. Open the `.pbix` file in Power BI Desktop if the project was built in Power BI.
2. Ensure any required source files are available at the expected paths.
3. Refresh the data if the source is connected and accessible.
4. Use the month and payment-status filters to explore the visuals.

If the project uses another BI tool, replace these instructions with the appropriate steps.

## Repository Structure

```text
PhonePe-Payment-Insights-Dashboard/
├── README.md
├── dashboard.png
├── PhonePe_Dashboard.pbix
└── data/
    └── dataset.csv
```

This is a suggested structure. Include only files that exist in your project, and do not upload confidential or restricted data.

## Future Improvements

- Add a date-range filter and drill-through pages.
- Include a detailed failed-transaction analysis.
- Compare transaction performance across regions, if regional data is available.
- Add transaction success-rate trends over time.
- Improve accessibility with clear labels, consistent formatting, and descriptive tooltips.
- Automate data refresh where the data source supports it.

## Conclusion

The PhonePe Payment Insights Dashboard brings important transaction and user metrics into one view. It is intended to make payment trends easier to monitor, compare, and communicate, while supporting further investigation of transaction performance.

---

**Author:** Your Name  
**Project:** PhonePe Payment Insights Dashboard  
**Purpose:** Data Analytics / Business Intelligence Portfolio Project
