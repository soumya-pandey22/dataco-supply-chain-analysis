# 🚚 Supply Chain Performance & Customer Analytics

Analysis of **DataCo Global's** supply chain dataset (180,000+ orders) to uncover delivery bottlenecks, profitability drivers, and customer value segments using Python.

---

## 📦 Dataset
**DataCo Smart Supply Chain for Big Data Analysis** (Kaggle)
🔗 Source: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis

## 🛠️ Tools Used
Python · Pandas · NumPy · Matplotlib · Seaborn

---

## 🔍 Key Findings

### 1️⃣ Shipping Mode Reliability 🚛
Second Class (+1.99 days) and First Class (+1.00 days) showed higher average delivery delays than Standard Class (-0.004 days), which was the most reliable shipping mode overall — despite being the cheapest option. Paying more didn't mean arriving faster.

### 2️⃣ Regional Delivery Performance 🌍
Central Asia recorded the highest average delivery delay among all regions, pointing to regional logistics challenges that may warrant a deeper look at carrier partners or warehouse coverage in that area.

### 3️⃣ Discount Has No Real Impact on Profit 💸
Correlation analysis (r = -0.003), discount-bucket comparison, and scatter plot visualization all confirm that discount rate has no meaningful relationship with profit ratio — margins stayed stable (~12%) regardless of discount level. Discounting may be driving volume, not profit erosion (or gain).

### 4️⃣ Category-Level Profit Concentration 🏕️
Sports and outdoor categories dominated profitability:
- 🎣 Fishing — $756K
- ⚽ Cleats — $495K
- 🏕️ Camping & Hiking — $427K

...far outperforming categories like 💻 Computers ($70K).

### 5️⃣ Customer Value Distribution (RFM Segmentation) 👥
- 🥇 High Value — 16.7%
- 🥈 Medium Value — 54.2%
- 🥉 Low Value — 29.2%

With over half of customers sitting in the Medium Value tier, there's a clear opportunity to move them up into High Value through targeted retention and loyalty efforts.

---

## 🗂️ Project Structure
1. 🧹 Data cleaning and preprocessing
2. ⏱️ Delivery delay analysis (by shipping mode and region)
3. 📈 Profit and discount analysis
4. 🎯 Customer segmentation using RFM (Recency, Frequency, Monetary)

---

## 💡 Recommendations
- 🔧 Investigate logistics partners and fulfillment routes in Central Asia to reduce delays
- 🎣 Double down on marketing/inventory for high-profit categories (Fishing, Cleats, Camping & Hiking)
- 🎯 Launch targeted campaigns to convert Medium Value customers into High Value segment
- 📊 Reassess discount strategy — since it isn't hurting margin, test whether it's effectively driving volume

---

## 📊 Visualizations
Key charts from the analysis (found in the `/images` or `/plots` folder):
- 🚛 Average delivery delay by shipping mode
- 🌍 Average delivery delay by region
- 💸 Discount rate vs. profit ratio (scatter plot)
- 🏕️ Total profit by category
- 👥 RFM customer segment distribution

---

## 🚧 Limitations
- Dataset reflects a fixed historical period and may not capture current supply chain conditions
- RFM segment thresholds were based on [quintiles / fixed cutoffs — specify which] and could shift with a different scoring method
- Delivery delay figures don't account for external factors like holidays, weather, or customs

