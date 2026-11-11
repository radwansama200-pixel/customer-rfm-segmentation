# Customer RFM Segmentation Analysis

Excel analysis segmenting 150 e-commerce customers by Recency, Frequency and Monetary value (RFM).

**Problem:** An online store needed to know which customers bring the most revenue and which ones are at risk of leaving, so it can target each group with the right offer.

**Tools:** Excel (formulas, scoring tables, summary table, chart)

**What I did:**

- Used a 150-customer dataset: last purchase date, orders per year, total spend
- Calculated Recency (days since last purchase, as of 21 Jun 2026), then scored Recency, Frequency and Monetary from 1 to 5 with IF formulas (fixed thresholds, e.g. 30 days or less = 5)
- Added the three scores into an RFM total and assigned each customer to one of 5 segments: Champions, Loyal Customers, Potential Loyalist, At Risk, Need Attention
- Built a summary table and chart of customers by segment

**Results:**

- 150 customers, total spend 378,531 EGP, average spend 2,524 EGP
- Loyal Customers is the largest segment (64 customers, 42.7%) and brings 48.3% of revenue
- Champions are only 12% of customers (18) but bring 20.7% of revenue, spending 4,348 EGP on average
- Champions + Loyal Customers are 55% of customers but 69% of revenue
- Potential Loyalists (57 customers, 38%) are the biggest growth opportunity: 1,869 EGP average spend, 3.9 orders per year
- Only 11 customers (7%) are At Risk or Need Attention

**Recommendation:** Give Champions and Loyal Customers early access and VIP perks, move Potential Loyalists up with loyalty offers, and send win-back campaigns to the 11 At Risk / Need Attention customers.

**Data:** Sample dataset (150 customers)

**File:** 02_Customer_RFM_Segmentation.xlsx
