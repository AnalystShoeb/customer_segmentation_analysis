## Project Background
This analysis focuses on **Summit Trust Bank** aiming to improve their customer targeting through segmentation.
The bank offer products like credit cards, loans, and investment portfolios. Active for over 15 years, the business primarily caters to individuals aged 20-60 with varying income and debt levels.
Key business goals include improving debt management offerings, upselling investment products, and ensuring sustainable customer growth.

Insights and recommendations are provided on the following key areas:

- **Category 1: Income Distribution and Segmentation** 
- **Category 2: Debt Management Across Segments** 
- **Category 3: Targeted Strategies for Age Groups** 
- **Category 4: Employment and Financial Stability Trends** 

The Python was used to for this segmentation analysis can be found here [link](https://github.com/AnalystShoeb/customer_segmentation_analysis/blob/main/Customer%20Segmentation%20Analysis.ipynb).
An interactive Tableau dashboard used to report can be found here [link](https://public.tableau.com/app/profile/shoebur.rahman/viz/CutomerSegmetationDashboard/CutomerSegmentationDashboard?publish=yes).

## Data Structure & Initial Checks

The companies main database structure as seen below consists of three tables: Demographics Table, Income and Debt Table, and Cluster Assignments. A description of each table is as follows:
- **Demographics Table:** Contains details about customer age, education, and employment.
- **Income and Debt Table:** Includes income, card debt, and other debt levels for each customer.
- **Cluster Assignments:** Python library K-Mean was used to develop the Customer Segmentation Table.

## Executive Summary
### Overview of Findings
Key Insights:
1.	Segment 4 contributes the highest income with a low debt-to-income ratio, making them ideal for premium offerings.
2.	Segment 3 has the highest debt levels, indicating a need for targeted debt management solutions.
3.	Older age groups (41-60) consistently show higher incomes, suggesting opportunities for investment-focused products.

![Customer Segmentation Dashboard](Customer%20Segmentation%20Dashboard.png)

## Insights Deep Dive

### Income Distribution and Segmentation:
* **Main insight 1.** Segment 4 accounts for 36% of total income, with an average income of $87K.
* **Main insight 2.** Segment 3 shows a debt-to-income ratio of 25%, significantly higher than the overall average.
* **Main insight 3.** Middle-income customers in Segment 2 are at risk of churn, requiring retention strategies.

### Debt Management Across Segments:
* **Main insight 1.** Customers in Segment 3 have total debts of $2.73M, indicating financial stress.
* **Main insight 2.** High-income customers (Segment 4) have the lowest debt-to-income ratio, highlighting financial stability.

### Targeted Strategies for Age Groups:
* **Main insight 1.** Customers aged 41-50 have the highest average income ($60.93K).
* **Main insight 2.** Younger customers (20-30) earn less ($28.19K), but they represent a growth opportunity for basic credit products.

## Recommendations:
Based on the insights above, the following actions are recommended:
* **Premium Offerings:** Introduce targeted debt management services for customers in Segment 3.
* **Debt Consolidation:** Focus on Segment 4 for investment products and exclusive credit card offerings.
* **Age-Specific Campaigns:** Create financial literacy campaigns and basic product bundles for customers aged 20-30.
* **Customer Retention:** Develop rewards programs and upsell opportunities for Segment 2.

## Assumptions and Caveats:
*	Missing income data for certain customers was estimated using average values from similar demographics.
*	December 2021 data was unavailable; trends were extrapolated based on historical data.
*	Certain edge cases with extreme debt-to-income ratios were excluded to avoid skewing results.

