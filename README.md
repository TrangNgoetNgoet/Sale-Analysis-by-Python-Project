# PROJECT: ANALYZING SALES PERFORMANCE & CUSTOMER BEHAVIOR (DEC 1, 2010 – NOV 30, 2011)

## 1. Project Introduction
This project focuses on **data cleaning** and **in-depth analysis** of key sales metrics and customer behavior over the period **December 1, 2010, to November 30, 2011**, presented through **10 primary charts**. Main objectives:

1. **Data Cleaning**:
   - Check for missing values.
   - Validate data types.
   - Correct negative values (data-entry errors).
   - Identify duplicates.

2. **Data Analysis (EDA)**:
   - Investigate monthly customer activity (MAU), order volume, average order value (AOV).
   - Assess top markets (by country) and categorize customers (loyal, losing, new...).

3. **Actionable Recommendations**:
   - Develop strategies to optimize revenue.
   - Retain loyal customers, attract new ones, tap into high-AOV markets.

---

## 2. Methodology & Implementation Steps

### 2.1 Data Cleaning
1. **Missing Values**: Count and decide whether to fill or drop them, depending on importance.  
2. **Data Types**: Ensure date columns are DateTime, price columns are float, quantity columns are int.  
3. **Negative Values**: Convert them to positive if confirmed as input errors, or remove if invalid.  
4. **Duplicates**: Detect duplicates (invoice, stock_code...) and handle them appropriately.

### 2.2 Exploratory Analysis & Visualization
- **Tools**: Python (Jupyter Notebook) – pandas, matplotlib, etc.  
- **Charts**: Focus on 10 key visuals:
  1. Monthly Active User (MAU)
  2. Monthly Orders & Total Order Amount
  3. Customer distribution by weekday & time slot
  4. Top 10 countries by total sales
  5. Top 10 countries by AOV
  6. Comparative market view (UK & Singapore) – top purchased products
  7. Proportion of new vs. old customers over time
  8. Average transaction value (ATV) of new customers returning monthly
  9. Quantity of each customer segment (Loyal, Losing, New…)
  10. Percentage of total revenue by each segment

---

## 3. Summary of Results & Chart Commentary

1. **Monthly Active User**: Held around ~1,000 early 2011, then jumped to ~1,600–1,900 from August onwards → Suggests a marketing push or product enhancements mid-year.  
2. **Monthly Orders & Total Amount**: Order count rose from 1,200–1,700 to 2,000–3,000 by year-end; sales grew from ~600k to 1.19 million in November → Plan inventory and staffing for Q4.  
3. **Customers by Day/Hour**: Peak usage at midday (11 AM–1 PM), minimal traffic early morning or late evening → Allocate staff to peak hours; consider off-peak promotions.  
4. **Top 10 Countries – Most Sales**: UK leads at 7.2 million, while others (Netherlands, Ireland…) range 200–300k → Intensify focus on the UK market.  
5. **Countries with Highest AOV**: Singapore ranks first (3,343.8), Netherlands at (2,801.1), Australia (2,028.5) → Target premium products in these high-AOV regions, plus localized strategies.  
6. **UK & Singapore – Top Products**: UK preferences revolve around retro/home décor (very high volume), Singapore around holiday/seasonal items (lower volume) → Tailor product offerings by local taste.  
7. **New vs. Old Customers Over Time**: Old customers increased from mid-year, new ones dropped (~1,000 down to ~200) and slightly rebounded in Q4 → Keep retention strategies robust, re-energize new-customer acquisition.  
8. **Avg Transaction Value (New Customer)**: Started around ~600, peaked at ~1,400 (Oct), then down to ~1,000 by November → Investigate what caused the upsell success.  
9. **Qty of Each Customer Type** (Loyal, Losing...): “Losing potential loyal” is highest at 1,506, “Low value” at 1,241; “Loyal” only 524 → A clear opportunity to upgrade the “Losing” cohort.  
10. **Percentage of Total Amount (Customer Type)**: Loyal yields ~46.5% of revenue, Losing + Lost ~30%, while New stands at merely 0.4% → Strengthen loyal customers further, while boosting new acquisitions.

---

## 4. Recommended Actions for the Business

1. **Prepare for Peak Season** (Q4):
   - Increase stock and staff from August–September.
   - Launch earlier promotions to sustain demand through year-end.

2. **Retain Loyal Customers**:
   - They account for nearly half of total revenue. Continue VIP perks, loyalty programs.
   - Expand upsell/cross-sell to maximize basket value.

3. **Grow New Customer Base**:
   - Enhance marketing channels (referrals, ads) and first-time offers.
   - Investigate why new customers declined mid-year, fix underlying issues.

4. **Expand Geographical Focus**:
   - The UK remains the top market. Tailor local marketing and products.
   - Exploit high-AOV countries like Singapore, Netherlands with premium lines.

5. **Address “Losing” Segments**:
   - “Losing potential loyal” is large; targeted incentives can convert them to Loyal.
   - “Low value” can be upgraded via combo deals or strategic promotions.

6. **Monitor & Segment**:
   - Continuously track each segment (Loyal, Lost, Low value, New).
   - Refine solutions for each group’s specific needs and behavior patterns.

---

## 5. Conclusion
This project offers a **comprehensive view** of monthly sales dynamics, customer behavior (peak hours, seasonal effects), and potential markets (by country and segment). By cleaning data and visualizing key insights, the company can make **data-driven decisions** on marketing, inventory, and strategies to retain high-value customers. Implementation of the above actions—consistently and cohesively—will significantly improve business performance.
