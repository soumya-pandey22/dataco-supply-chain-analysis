# Supply Chain Performance & Customer Analytics

Analysis of DataCo Global's supply chain dataset (180,000+ orders) to uncover delivery bottlenecks, profitability drivers, and customer value segments using Python.

## Dataset
DataCo Smart Supply Chain for Big Data Analysis (Kaggle)
Source: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn

## Key Findings

**1. Shipping Mode Reliability**
Second Class (1.99 days) and First Class (1.00 days) showed higher average delivery delays than Standard Class (-0.004 days), which was the most reliable shipping mode overall.

**2. Regional Delivery Performance**
Central Asia recorded the highest average delivery delay among all regions, pointing to regional logistics challenges.

**3. Discount Has No Real Impact on Profit**
Correlation analysis (-0.003), discount-bucket comparison, and scatter plot visualization all confirm that discount rate has no meaningful relationship with profit ratio — margins stayed stable (~12%) regardless of discount level.

**4. Category-Level Profit Concentration**
Sports and outdoor categories — Fishing ($756K), Cleats ($495K), and Camping & Hiking ($427K) — generated the highest total profit, far outperforming categories like Computers ($70K).

**5. Customer Value Distribution (RFM Segmentation)**
Only 16.7% of customers are High Value, while 54.2% are Medium Value and 29.2% are Low Value — highlighting an opportunity to convert Medium Value customers into High Value ones.

## Project Structure
- Data cleaning and preprocessing
- Delivery delay analysis (by shipping mode and region)
- Profit and discount analysis
- Customer segmentation using RFM (Recency, Frequency, Monetary)
