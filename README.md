# 2Market Sales and Marketing Analysis

## Project Overview

This project analyzes customer demographics, top-selling products, and advertisement effectiveness for **2Market**, an international supermarket. The company is facing a decline in profits and aims to improve sales by understanding its customer base and optimizing its marketing strategies. Using data analytics, the goal is to uncover insights into customer behaviors, product preferences, and the performance of various advertisement channels to drive more targeted marketing efforts and better resource allocation.

## Business Problem

2Market has been experiencing a decline in profits, and the company lacks critical insights into customer demographics, top-selling products, and advertisement performance. This project aims to:

- Understand the demographics of 2Market’s typical consumer.
- Identify top-selling products and product shares across various customer categories.
- Analyze the effectiveness of different advertisement channels to optimize marketing strategies.

These insights will inform 2Market’s resource allocation, advertising campaigns, and help improve the overall sales performance.

## Analytical Approach

The analysis was conducted using two datasets provided by the 2Market team:

- **marketing_data**: Contains customer demographic information, purchase behaviors, and recency data.
- **ad_data**: Contains advertisement data, including the success rates and leads generated.

### Key Steps

1. **Data Cleaning**: 
   - Removed duplicates and cleaned inconsistent records.
   - Handled outliers in age and income columns using the interquartile range (IQR) method.
   - Removed customers with 0 purchases from the dataset.

2. **Exploratory Data Analysis (EDA)**:
   - Conducted a thorough analysis using both Excel and SQL to uncover key trends in customer demographics, purchases, and advertisement effectiveness.
   - Utilized SQL for deeper exploration and summarization of large datasets.

3. **Customer Segmentation**:
   - Divided customers into three segments based on purchase recency:
     - **Current Customers** (purchases within the last 30 days)
     - **Irregular Customers** (purchases between 31-60 days ago)
     - **Lost Customers** (purchases more than 60 days ago)

4. **Dashboard Development**:
   - Created four interactive dashboards in Tableau to visualize key insights:
     1. **Demographics Dashboard**: Provides a profile of the typical consumer at 2Market.
     2. **Customer Profile Dashboard**: Analyzes average customer characteristics across sales and purchases.
     3. **Products Dashboard**: Displays the share of each product category across customer demographics.
     4. **Advertisement Dashboard**: Analyzes advertisement success rates across demographics.

## Key Insights

1. **Typical Consumer Profile**: 
   - Most typical consumers are from Spain, aged 45-55, married, and have a graduate degree.

2. **Purchasing Behavior**:
   - The average customer makes 9.96 purchases per year, with 5.84 purchases in-store and 4.12 purchases online.

3. **Top-Selling Products**:
   - Alcoholic drinks and meat are the top-selling products, with consumption patterns varying significantly by age and income.

4. **Advertising Effectiveness**:
   - Older age groups and higher income brackets are more responsive to advertising.
   - Advertisement channels with a success rate of over 7% should be prioritized for cost efficiency.

5. **Optimization Opportunities**:
   - By targeting the right demographics and focusing on high-performing advertisement channels, 2Market can optimize marketing efforts and reduce costs.

## Visualizations

This project includes several Tableau dashboards that provide detailed insights into 2Market's customer base, product sales, and advertisement effectiveness. You can find the Tableau file in the project folder for interactive exploration.

### Dashboards:

1. **Demographics Dashboard**: Displays a demographic profile of 2Market’s typical consumer.
2. **Customer Profile Dashboard**: Shows detailed customer information across various sales and purchase categories.
3. **Products Dashboard**: Highlights product share and demographic impacts on product sales.
4. **Advertisement Dashboard**: Analyzes the success of different advertisement types across various demographics.

## Files in this Repository

- `marketing_data.csv` – The cleaned marketing data with customer demographics and purchase behaviors.
- `ad_data.csv` – The advertisement data with campaign success rates and leads.
- `Technical_Report.pdf` – Technical report summarizing the analysis, insights, and recommendations.
- `Dashboard_Tableau.twb` – Tableau workbook containing the interactive dashboards.

## Conclusion

This project highlights the importance of understanding customer demographics and purchasing behavior for improving marketing strategies. By focusing on the right product categories, understanding the impact of advertisements, and using data-driven insights, 2Market can optimize its resources and enhance its profitability.

## Future Recommendations

- Further analysis of customer order data over time to identify trends and seasonal variations.
- Exploration of more advertising channels and campaigns to assess their effectiveness.
- Implementing personalized marketing campaigns targeting the most responsive customer segments.
