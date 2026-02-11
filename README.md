# Customer Revenue & Retention Analysis

## Business Context
Olist is a Brazilian marketplace connecting customers and sellers nationwide. While transaction volumes appear strong, leadership requires clarity on revenue quality, operational efficiency, and long-term growth sustainability.

This project evaluates:
  1. Revenue concentration risk
  2. Operational revenue leakage
  3. Customer retention sustainability
  4. Dependence on acquisition-driven growth

## Key Business Questions
1. Is revenue concentrated among a small group of customers?
2. How much revenue is unrealized due to cancellations?
3. Are customers returning after their first purchase?
4. Is growth driven by retention or continuous acquisition?

## Analytical Approach
The analysis was structured into four phases:
1. Revenue Profiling -
  i) Calculated total and realized revenue
  ii) Analyzed revenue by order status
  iii) Identified operational revenue leakage

2. Revenue Concentration -
  i) Computed revenue per customer
  ii) Segmented customers using NTILE(10)
  iii) Measured contribution of top 10% customers

3. Retention & Repeat Rate -
  i)Calculated orders per customer
  ii) Measured repeat customer rate

4. Cohort Analysis -
  i) Grouped customers by first purchase month
  ii) Computed cohort index using TIMESTAMPDIFF
  iii) Built cohort activity matrix

## Key Findings
1. Revenue Concentration: Top 10% of customers contribute ~40% of total revenue, indicating dependency risk.
2. Revenue Realization: A portion of revenue is associated with cancelled orders, highlighting operational leakage.
3. Repeat Rate: Observed repeat rate is 0% (within available dataset), indicating acquisition-driven growth.
4. Cohort Behavior: Customer activity is concentrated in acquisition month, with no observable retention beyond month zero.

## Business Implications
1. Growth appears heavily acquisition-dependent.
2. Customer lifetime value is limited under current behavior patterns.
3. Revenue concentration increases strategic vulnerability.
4. Operational inefficiencies reduce realized revenue.
5. Lack of repeat behavior poses long-term sustainability risk.

## Strategic Recommendations
1. Strengthen Retention Strategy -
i) Implement loyalty and post-purchase engagement programs
ii) Incentivize second purchases

2. Reduce Revenue Leakage -
i) Diagnose cancellation drivers
ii) Improve seller performance monitoring and inventory controls

3. Protect High-Value Customers -
i) Identify top revenue decile
ii) Develop targeted engagement initiatives
