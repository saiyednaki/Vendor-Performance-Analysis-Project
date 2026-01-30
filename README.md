# Vendor-Performance-Analysis-Project

**Overview**

Effective inventory and sales management are crucial for optimizing profitability in the retail and wholesale industry. This analysis focuses on identifying underperforming brands, evaluating vendor performance, and optimizing pricing and inventory strategies to improve efficiency and profitability.

**The main objectives of this analysis are:**
Identify underperforming brands requiring promotional or pricing adjustments.
Determine top vendors contributing to sales and gross profit.
Analyze the impact of bulk purchasing on unit costs.
Assess inventory turnover to reduce holding costs and improve operational efficiency.
Investigate profitability variance between high-performing and low-performing vendors.

**Data Exploration Insights**

**Summary Statistics**

  - Gross Profit: Minimum value of -52,002.78 indicates potential losses due to high costs or heavy discounts.
  - Profit Margin: Minimum of -∞, showing cases where revenue is zero or lower than costs.
  - Sales Quantity & Sales Dollars: Some products show zero sales, suggesting slow-moving or obsolete inventory.

**Outliers & Variations**
  - Purchase & Actual Prices: Maximum values are significantly higher than the mean, indicating premium products.
  - Freight Costs: Range from 0.09 to 257,032.07, highlighting logistical inefficiencies.
  - Stock Turnover: Ranges from 0 to 274.5, indicating variability in product sales velocity.

**Data Filtering**

- To ensure analysis reliability, data points were filtered to exclude:
- Gross Profit ≤ 0
- Profit Margin ≤ 0
- Total Sales Quantity = 0

**Correlation Insights**
  - Purchase price has a weak correlation with sales dollars and gross profit.
  - Total purchase quantity correlates strongly with total sales quantity (0.999), confirming effective inventory turnover.
  - Profit margin has a slight negative correlation with total sales price (-0.179).
  - Stock turnover shows weak negative correlation with gross profit and profit margin.

**Key Findings**

1. Brands for Promotional or Pricing Adjustments:
    - 198 brands with low sales but high profit margins could benefit from targeted promotions or price adjustments.
2. Top Vendors by Sales & Purchase Contribution:
    - Top 10 vendors contribute 65.69% of total purchases, highlighting dependency on a few suppliers.
3. Impact of Bulk Purchasing:
    - Vendors buying in bulk achieve 72% lower unit costs, supporting cost-effective pricing strategies.
4. Vendors with Low Inventory Turnover:
    - Unsold inventory capital totals $2.71M, indicating slow-moving stock and high holding costs.
5. Profit Margin Comparison:
    - High-volume vendors have lower margins (~31%) compared to low-performing vendors (~41%), suggesting pricing or market reach inefficiencies.
6. Statistical Validation:
    - Hypothesis testing confirms a significant difference in profit margins between top-performing and low-performing vendors.

**Actionable Recommendations**
- Pricing Optimization: Re-evaluate pricing for low-sales, high-margin brands to increase volume without sacrificing profitability.
- Vendor Diversification: Reduce reliance on a few vendors to mitigate supply chain risks.
- Leverage Bulk Purchasing: Maintain competitive pricing while optimizing inventory costs.
- Manage Slow-Moving Inventory: Adjust purchase quantities, launch clearance sales, or revise storage strategies.
- Enhance Marketing & Distribution: Improve visibility and sales for low-performing vendors.

**Conclusion**

By implementing these recommendations, retail and wholesale businesses can achieve sustainable profitability, reduce operational risks, and improve inventory and vendor management efficiency.
