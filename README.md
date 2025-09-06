# Refrigerate the Risk: Optimizing Inventory and Operations for Profit Enhancement in Dairy Retail

*BDM Capstone Project*

**Submitted by:**  
**Name:** Mili Parashar  
**Roll Number:** 23f2004291  
**Program:** IITM Online BS Degree Program  
**Institution:** Indian Institute of Technology, Madras, Chennai, Tamil Nadu, India, 600036  

---

## 📖 Project Overview
This project analyzes and optimizes the operations of **Kribhco Karmachari Sahkari Dhiran Purvarsh Society**, a dairy and ice cream outlet in Surat serving 420+ customers.  

The store faces recurring challenges:
- Overstocking & stockouts  
- Spoilage due to power outages and weak cold-chain infrastructure  
- Delivery inefficiencies  

Data collected (April 2024 – March 2025) from **sales/purchase registers, supplier invoices, and environmental logs** was cleaned, structured, and analyzed to provide actionable, low-cost recommendations.  

---

## 🛠️ Tools & Libraries Used
- **Python:** pandas, numpy, matplotlib, seaborn, scikit-learn, prophet  
- **Excel:** Initial cleaning, EOQ/ROP calculations  
- **Visualization:** Matplotlib & Seaborn (trend, correlation, Pareto, spoilage charts)  
- **Data Modeling:** Prophet (time series), Gradient Boosting Regressor, Random Forest Classifier  

---

## 📊 Methods & Analysis
1. **Data Cleaning & Preprocessing**
   - Standardized naming, resolved missing values  
   - Star schema with fact & dimension tables for sales/purchases  
   - Integrated weather data for external factor analysis  

2. **Demand Trend Analysis**  
   - Seasonal peaks: Milk (monsoon), Ice Cream (summer)  

3. **RFM Analysis (Customers & Products)**  
   - Identified top loyal customers (high recency, frequency, monetary value)  
   - Highlighted inactive customers & underperforming SKUs  

4. **Demand Forecasting**  
   - Prophet for milk demand (clear downward trend)  
   - Gradient Boosting Regressor for ice cream (captures non-linear patterns)  

5. **EOQ & ROP Modeling**  
   - Milk EOQ ≈ 1405 L, ROP ≈ 406 L  
   - Ice Cream EOQ ≈ 208 units, ROP ≈ 30 units  

6. **Overstock Risk Classification (Random Forest)**  
   - Accuracy: **83%**  
   - Flagged SKUs at risk of overstock/spoilage  

7. **Correlation Analysis**  
   - Ice cream sales positively correlated with high temperature (>80°F)  
   - Weak link between milk demand and weather  

8. **SKU-level Spoilage Analysis**  
   - Products like V-240 & V-300 most spoiled  

9. **Cold Chain Performance Score**  
   - Highlighted weak refrigeration and outage management  

10. **Pareto Analysis (80/20 Rule)**  
   - 20% of SKUs contributing 80% of revenue  

11. **Delivery Pattern Clustering (K-Means)**  
   - Identified high/medium/low demand delivery clusters  

---

## 📈 Results & Insights
- **Milk:** Amul Gold & Shakti dominate sales  
- **Ice Cream:** Amul leads, Vadilal secondary, Havmor niche  
- **Forecasting:** Milk demand trending downward, ice cream demand highly temperature-sensitive  
- **Overstock Risks:** Combo Vanilla Pack & Chocolate Brownie Tricone Cone identified as high-risk items  
- **Spoilage:** Significant losses from cold-chain failures, especially during peak summer months  

---

## ✅ Recommendations
- **Inventory Management**  
  - Implement EOQ/ROP-driven reordering  
  - Prioritize Category A SKUs, phase out Category C  

- **Cold Storage Improvements**  
  - Buy ice cream stock in **7–10 day cycles**  
  - Use **insulated ice boxes / inverter backup** for outages  
  - Apply **FIFO labeling** for perishables  

- **Delivery Optimization**  
  - Cluster routes by area, stagger peak-day deliveries  
  - Use protective packaging to prevent damage  

---

## 🚀 Implementation Impact
By applying the above strategies:  
- Reduced **spoilage and wastage costs**  
- Improved **cash flow & profit margins**  
- Enhanced **customer satisfaction & retention**  
- Created a **resilient, data-driven business model** with minimal investment  

---

## 📂 Repository Contents 
- [BDM Presentation](https://www.canva.com/design/DAGvZGPaKJs/6Lw1f5zLTHvHZK5li9jy0w/edit?utm_content=DAGvZGPaKJs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 
- [BDM-Cleaned Data.xlsx](https://docs.google.com/spreadsheets/d/1c9ezZvWDVIatw2t3mHNt-RjFgijO8D8F/edit?usp=sharing&ouid=113051615845337562697&rtpof=true&sd=true)


