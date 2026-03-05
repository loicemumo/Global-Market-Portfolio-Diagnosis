# Global Sales Portfolio Analysis: Identifying High-Performing Markets and Product Segments

## Introduction
This project analyzes a global sales dataset [sourced from GitHub Gist](https://gist.github.com/denandreychuk/b9aa812f10e4b60368cff69c6384a210) containing country-level performance records across multiple regions, product categories, and sales channels.  

The objective is to understand how **revenue and profitability vary across markets and product segments**, and to identify where investment can maximize growth while managing geographic and channel concentration risk.  

---

## 🛠️ Tech Stack
- **Python**: Data wrangling and analysis  
- **Pandas & NumPy**: Data manipulation and aggregation  
- **Matplotlib & Seaborn**: Visualization of trends and concentration risks  
- **Scikit-learn**: Normalization and comparative analysis  
- **Statistical Diagnostics**: Revenue concentration, margin efficiency, and investment scoring  

---

## ⚙️ Methodology
1. **Data Exploration**  
   - Loaded and cleaned 100 records of global sales data.  
   - Reviewed summary statistics for units sold, pricing, revenue, and profit.  

2. **Revenue Diagnostics**  
   - Aggregated revenue by **region**, **item type**, and **sales channel**.  
   - Visualized concentration risks using Pareto-style charts.  

3. **Revenue Drivers**  
   - Compared categories by **volume (units sold)**, **pricing power**, and **profit margin**.  
   - Standardized metrics for cross-category comparison.  

4. **Channel & Regional Efficiency**  
   - Assessed total revenue, profit, and margin by **offline vs. online channels**.  

5. **Investment Strategy**  
   - Ranked regional-channel segments using a composite **Investment Score** (revenue + margin).  
   - Modeled impact of a 10% incremental investment in top-performing segments.  

---

## 📊 Key Findings
- **Regional Concentration:** Sub-Saharan Africa and Europe together account for **over 50% of total revenue**.  
- **Product Categories:** Cosmetics, Office Supplies, and Household goods drive **~70% of revenue**, while Fruits contribute almost nothing.  
- **Revenue Drivers:**  
  - Volume alone is insufficient (e.g., Beverages sell most units but generate weak revenue).  
  - Pricing power is critical (Household and Office Supplies succeed despite lower volumes).  
  - Cosmetics dominate by balancing both **volume and pricing strength**.  
- **Sales Channels:**  
  - Offline sales generate **USD 79.09M revenue** and **USD 24.92M profit**.  
  - Online sales achieve higher efficiency with a **33.04% profit margin**.  

---

## Recommendations
- Focus investment on **Sub-Saharan Africa (Offline)**, **Europe (Online)**, and **Australia & Oceania (Offline)**.  
- These segments combine **high revenue contribution** with **strong profit margins**, offering the best return on incremental investment.  
- A targeted **10% increase in investment** in these segments is projected to deliver:  
  - **+USD 4.52M in revenue** (+3.3%)  
  - **+USD 1.52M in profit** (+3.4%)  

---

## Next Steps
- Extend analysis to **profitability by product-region combinations**.  
- Incorporate **time-series trends** to evaluate sustainability of high-performing segments.  
