<h1 align="center">🛒 Zepto Product Data Analysis</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20|%20Seaborn-orange" alt="Visualization">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" alt="Status">
</p>

---

## 📘 Project Overview

This project analyzes **product-level data scraped from Zepto** to uncover pricing trends, discount patterns, and customer behavior insights.

Using Python (Pandas, Matplotlib, Seaborn), we performed **data cleaning, univariate & bivariate analysis**, and derived actionable business insights.

---

## 🎯 Objective

Understand **category-level pricing, discounting, and customer engagement** on Zepto to answer key business questions:

- How are prices and ratings distributed across categories?  
- Do discounts influence customer satisfaction?  
- Which categories or products dominate sales and engagement?

---

## 🧭 Workflow & Methodology

1. **📥 Data Loading & Overview** — Imported raw scraped data and inspected structure.  
2. **🧹 Data Cleaning & Preprocessing** — Handled missing values, removed inconsistencies, and standardized numeric fields.  
3. **📊 Univariate Analysis** — Analyzed individual metrics like price, rating, and discount distribution.  
4. **🔗 Bivariate Analysis** — Explored relationships (price vs. rating, discount vs. rating, etc.).  
5. **💡 Business Insights** — Summarized patterns and formulated strategic recommendations.

---

## 🧠 Key Insights

### 🔹 Univariate Insights
- Most Zepto products fall under **snacks**, **bread**, and **milk** categories.  
- Prices are typically concentrated between **₹40–₹120**.  
- Ratings are high overall (**4.0–4.8**), reflecting strong customer satisfaction.

### 🔸 Bivariate Insights
- **Premium categories** like bakery and packaged foods cost more.  
- **Discounts** show **minimal correlation** with ratings — they don’t directly boost satisfaction.  
- **Review counts** are heavily skewed — few products dominate engagement.

---

## 🧾 Summary

Zepto’s marketplace has a strong presence in **affordable food categories**, where premium items are few but well-rated.  
Future analyses could focus on:

- 📉 **Price Elasticity** (rating vs. discount)  
- 📆 **Seasonal Demand Trends**  
- 🏷️ **Stock Optimization**

---

## 🛠️ Tech Stack

| Tool / Library | Purpose |
|-----------------|----------|
| 🐍 **Python 3.9+** | Core programming language |
| 🧮 **Pandas** | Data manipulation & cleaning |
| 📊 **Matplotlib / Seaborn** | Data visualization |
| 📁 **Jupyter Notebook** | Interactive analysis & reporting |

---

## 📦 Exporting Data

To save cleaned data locally:

```python
import os
download_path = os.path.join(os.path.expanduser("~"), "Downloads", "zepto_products_cleaned.csv")
df.to_csv(download_path, index=False)
print(f"✅ Exported Clean Data → {download_path}")
