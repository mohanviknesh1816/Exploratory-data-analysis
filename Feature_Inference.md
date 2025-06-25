##  feature Summary & Inference for Selected Features

### 1. Total_Trans_Amt

 Histogram:
- Shows most customers spend between 2,000 and 8,000.
- Right-skewed with a few very high spenders.

 Boxplot:
- Several high-value outliers (some customers spend over 15,000).

Inference:
- Higher transaction amounts may indicate high-value customers.
- Outliers could be targeted for premium offers.

---

### 2. Total_Trans_Ct

 Histogram:
- Most customers have 40–80 transactions per year.
- Peak around 70; very few below 20 or above 100.

 Boxplot:
- A few low-usage outliers are present.

Inference:
- Transaction count is a strong signal of card usage.
- Low count may indicate disengaged customers at risk of churn.

---

### 3. Credit_Limit

📉Histogram:
- Spread from 1,000 to 25,000+.
- Most customers fall between 5,000 and 15,000.

 Boxplot:
- Wide range with visible high-end outliers.

 Inference:
- High variance suggests multiple customer tiers (entry-level to premium).
- High limits don’t necessarily correlate with spending.

---

### 4. Avg_Utilization_Ratio

 Histogram:
- Most customers use less than 30% of their credit.
- A few customers use nearly 100%.

 Boxplot:
- Several high outliers near 1.0 (fully utilized).

inference:
- Low utilization indicates healthy behavior.
- Very high utilization may signal financial risk or credit stress.

### 🔗 Correlation & Pairwise Relationships

 Correlation Matrix:
- Total_Trans_Amt ↔ Total_Trans_Ct: Strong positive correlation.
- Credit_Limit ↔ Avg_Utilization_Ratio: Mild negative relationship.

 Pairplot:
- Clear linear trend between transaction count and amount.
- No multicollinearity detected between features.

 Inference:
- Total transaction count and amount are directly related.
- Utilization ratio provides useful credit behavior insights independent of total spend.

