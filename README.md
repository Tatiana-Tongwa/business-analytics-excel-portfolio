# Business Analytics Excel Portfolio

A collection of Excel-based business analytics projects demonstrating data cleaning,
Power Query, pivot tables, interactive dashboards, risk analysis, and data-driven
decision making.

## Projects

1. P2P Loan Risk & Return Analysis
2. U.S. Business Analytics Job Market Dashboard

This section would explain the lending analysis based on the credit-scoring dataset. The underlying task is to identify borrower characteristics associated with better loan performance while balancing offered interest returns against delinquency/default risk. The dataset includes borrower demographics, income and liabilities, credit history, interest rates, delinquency indicators, and actual defaults.

### Objective

Identify borrower segments that offer an attractive balance between
investment return and credit risk.

### Analysis

The analysis uses Excel filtering, pivot tables, pivot charts, and
borrower segmentation to examine relationships between:

- Credit score
- Interest rate
- Employment
- Income and free cash flow
- Borrower age
- Delinquency history
- Loan defaults
- Geographic location

### Final Lending Strategy

The analysis narrowed the investment universe to a group of borrowers
with stronger credit characteristics while maintaining attractive
interest returns.

Key criteria included:

- Finnish borrowers
- Credit score between 800 and 1000
- No recorded default
- No significant delinquency history
- Active employment
- Positive repayment capacity
- Target interest rate approximately 10–25%

The resulting screen identified approximately **61 potential borrowers**
meeting the selected risk-return criteria.

## 2. U.S. Business Analytics Job Market Dashboard

This is a separate analytical project inside the same workbook. It uses Power Query to consolidate multiple monthly job datasets, merge job locations with state information, calculate average salary during transformation, and feed an interactive dashboard.

### Objective

Analyze the U.S. Business Analytics job market to understand:

- Which states offer the highest salaries
- Which sectors offer the strongest compensation
- Where the greatest number of opportunities exist
- Which companies offer the highest salaries
- How employer size/revenue changes the market picture

### Data Pipeline

Power Query is used to:

1. Import multiple monthly job-market files
2. Consolidate them into one dataset
3. Merge job locations with state data
4. Transform salary fields
5. Calculate average salary
6. Load the transformed data into the dashboard

### Key Findings

- California had the highest average salary at approximately **$92.8K**
- Texas had the largest number of job postings
- Media, Real Estate, and Consumer Services were among the
  highest-paying sectors
- Information Technology had the largest number of opportunities
- Overall average salary was approximately **$77.6K**

## Skills Demonstrated

### Excel
- Advanced filtering
- Pivot tables
- Pivot charts
- Slicers
- Dashboard design
- Data visualization

### Power Query
- Multi-file consolidation
- Data transformation
- Dataset merging
- Calculated columns
- Refreshable data pipelines

### Business Analytics
- Credit-risk analysis
- Risk-return segmentation
- Job-market analysis
- KPI development
- Decision-support analysis
- Insight communication
