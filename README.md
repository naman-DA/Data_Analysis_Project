# Vendor_Performance_Analysis_Project
## BUSINESS PROBLEM
Effective inventory and sales management are critical for optimizing profitability in the retail and wholesale industry. Companies need to ensure that they are not incurring losses due to inefficient pricing, poor inventory turnover, or vendor dependency. 
The goal of this analysis is to:

•	Identify underperforming brands that require promotional or pricing adjustments.

•	Determine top vendors contributing to sales and gross profit.

•	Analyze the impact of bulk purchasing on unit costs.

•	Assess inventory turnover to reduce holding costs and improve efficiency.

•	Investigate the profitability variance between high-performing and low-performing vendors.

## Exploratory Data Analysis Insights
## Summary Statistics

 

       
 
Negative and Zero Values: 
Gross Profit: Minimum of -1239894.18, indicating potential losses due to high costs or heavy discounts. This could be due to sellling products at lower prices than their purchase costs.
Profit Margin: Has a minimum of -inf, which suggests instances where revenue is zero or even lower than the total cost, leading to extreme negative profit margins.
Total Sales Quantity & Sales Dollars: Some products show zero sales, indicating they were purchased but never sold. These may be slow-moving or obsolete stock, leading to inventory inefficiencies.
Outlies Detected by High Standard Deviations:
Purchase & Actual Prices: The maximum values (5,681.81 & 7,499.99) are significantly higher than the mean (21.89 & 32.19), indicating premium product offerings.
Freight Cost: Extreme variation from to suggests logistics inefficiencies, bulk shipments, or erratic shipping costs across different products.
Stock Turnover:  Ranges from to suggesting some products sell rapidly while others remain unsold for long periods. A value greater than 1 indicates that sales for a product exceed the purchased quantity due to older stock fulfilling orders.
 
 ## Data Filtering:
 To enhance the reliability of the insights, we removed inconsistent data points where:
•	Gross Profit <= 0 (to exclude transactions leading to losses).
•	Profit Margin <= 0 (to ensure analysis focuses on profitable transactions).
•	Total Sales Quantity = 0 (to eliminate inventory that was not never sold). 
 ## Correlation Insights
 
Purchase Price vs. Total Sales Dollars & Gross Profit: Weak correlation (-0.012 & -0.016), indicating that price variations do not significantly impact sales revenue or profit.
Total Purchase Quantity vs. Total Sales Quantity: Strong correlation (0.999), confirming efficient inventory turnover.
Profit Margin vs. Total Sales Price: Negative correlation (-0.179), suggesting increasing sales prices may lead to reduced margins, possibly due to competitive pricing pressures.
Stock Turnover vs. Gross Profit & Profit Margin: Weak negative correlation (-0.038 & -0.055), indicating that faster stock turnover does not necessarily equate to higher profitability.

## Research Questions & Key Findings
1.	Brands for Promotional or Pricing Adjustments
 
198 brands exhibit lower sales but higher profit margins, which could benefit from targeted marketing, promotions, or price optimizations to increase volume without compromising profitability.
 
2.	Top Vendors by Sales & Purchase Contribution
The top 10 vendors contribute 75.14% of total purchases, while the remaining vendors contribute only 24.86%. This over-reliance on a few vendors may introduce risks such as supply chain disruptions, indicating a need for diversification.
 
3.	Impact of Bulk Purchasing on Cost Savings
Vendors buying in large quantities receive a 72% lower unit cost ($11.25 per unit vs. higher unit costs in smaller orders).
Bulk pricing strategies encourage large orders, increasing total sales while maintaining profitability. 
 
4.	Profit Margin Comparison: High vs. Low-Performing Vendors
 
   Low-performing vendors maintains higher margins but struggle with sales volumes, indicating potential pricing inefficiencies or market reach issues.
Actionable Insights:
•	Top-Performing vendors: Optimize profitability by adjusting pricing, reducing operational costs, or offering bundled promotions.
•	Diversify vendors partnerships to reduce dependency on suppliers and mitigate supply chain risks.
•	Leverage bulk purchasing advantages to maintain competitive pricing while optimizing inventory management.’
•	Optimize slow-moving inventory by adjusting purchase quantities, launching clearance sales, or revising storage strategies.
•	Enhance marketing and distribution strategies for low-performing vendors to drive higher sales volumes without compromising profit margins.
•	By implementing these recommendations, the company can achieve sustainable profitability, mitigate risks, and enhance overall operational efficiency. 
