# Superstore Sales and Profitability Analysis

# Project Objective

Analyze a year of retail sales data to evaluate revenue trends, investigate profitability challenges, identify underperforming products and regions, and recommend data-driven actions to improve business performance.

# Tools Used

Google Colab: Data cleaning, exploratory analysis, monthly trend analysis, and Python visualizations.
SQL (SQLite): Monthly revenue queries, product profitability analysis, discount analysis, and regional comparisons.
Power BI: Interactive dashboard, DAX measures, date modeling, and KPI reporting.

# Business Questions

How did sales and profit change throughout the selected year?
Which product categories and subcategories contributed most and least to profit?
How did profitability vary across discount levels?
Which regions and customer segments underperformed?
What actions could improve revenue and profit?

# Key Findings
From the beginning to the end of the year, sales nearly doubled, rising from $43,971.37 in January to $83,829.32 in December. Month to month, sales fluctuated, with February, April, July, October, and December showing a decrease from the prior month. Overall profit increased from the beginning to the end of the year, rising from $ 7,140.11 in January to $ 8,483.35 in December. Like sales, profit showed fluctuations throughout the year.
Office Supplies was the top contributor to profit and sales, with Technology following behind, and Furniture last. This is shown in subcategories, with copiers, accessories, phones, paper, and appliances being the top 5 contributors to profit, 3 of which are known office supplies. Additionally, Tables were far and away the least profitable, with machines, supplies, bookcases, and fasteners following. 
A noticeable trend exists between profitability and discount rate. The higher the discount rate, the lower the profit. This is clear throughout the data, as the 0% discount rate generated the most profit. From there, profit plummets with 0-10%, sees a rare increase with 10-20%, but then falls at the next interval and gradually gets lower.  
The Central Region underperformed, with the lowest profit at $7550.84 and the lowest revenue per unit.

# Recommendations

Profit declined sharply when the discount rate exceeded 20%, so most discounts should be capped at 20%, with a few exceptions. The data also supports this: $104157.71 in profit at a 0% discount rate, $3300.59 at 0%-10%, and $33550.86 at 10%-20 %.
February, April, May, June, and July saw the lowest sales of the year, so additional sales could be used during these months to motivate customers to spend 
Copiers and Office Supplies as a whole were the best-selling products, so more focus should go into selling office supplies 

# Limitations

The Sample Superstore dataset represents a fictional retail business and does not establish the financial performance of an actual named company. Historical trends and associations do not prove causation. Recommendations should be validated through further analysis and, where appropriate, controlled business experiments.


# Deliverables
Google Colab notebook
SQL query file
Cleaned dataset
Power BI dashboard
Executive summary and recommendations
