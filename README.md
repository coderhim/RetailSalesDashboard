# 📊 Superstore Sales Analytics Dashboard

A data analytics and visualization project to uncover business insights from a retail superstore dataset using **Python** and **Power BI**.

---

## 🚀 Project Overview

This project explores historical sales data from a fictional superstore to analyze sales performance, profitability, shipping efficiency, and customer behavior across different regions and product categories.  
It combines **data cleaning in Python** with **interactive dashboarding in Power BI**, mimicking real-world business intelligence workflows.

---

## 🧰 Tools & Technologies

- **Python**: Data cleaning, preprocessing, and exploratory analysis
- **Pandas, Matplotlib**: Initial analysis and insights
- **Power BI**: Interactive dashboard creation and visualization

---

## 📂 Dataset

- **Source**: [Kaggle - Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Rows**: ~10,000
- **Fields**: Order info, customer segment, product category, shipping dates, sales, profit, discount, and location

---

## 🧹 Data Cleaning & Preprocessing (Python)

Key steps:
- Parsed `Order Date` and `Ship Date` into datetime format
- Created a new column `Shipping Delay = Ship Date - Order Date`
- Verified data types and missing values
- Aggregated sales and profit by category/sub-category
- Resampled monthly sales to observe trends

Code is available in [`superstore_analysis.ipynb`](./superstore_analysis.ipynb)

---

## 📊 Power BI Dashboard

The interactive dashboard includes:

- ✅ **KPI Cards**: Total Sales, Total Profit, Avg Shipping Delay  
- 📈 **Monthly Sales Trend**: Line chart of revenue over time  
- 📊 **Regional Sales**: Bar chart comparing performance by region  
- 🧩 **Category-wise Sales Breakdown**: Tree map for category/sub-category  
- 🏆 **Top 10 Profitable Cities**: Sorted table  
- 🔍 **Interactive Slicers**: Segment & Shipping Mode filters  

> 📁 Dashboard file: [`Superstore_Dashboard.pbix`](./Superstore_Dashboard.pbix)

---

## 🔍 Key Insights

- 📱 Phones & Chairs are the top revenue-generating sub-categories  
- 🪑 Tables and Bookcases are unprofitable — need deeper cost analysis  
- 📈 Strong sales seasonality visible around Q4  
- 🚚 Central region has the longest average shipping delays  
- 🏙️ Profit concentrated in specific cities — useful for targeting

---

## 📌 Business Recommendations

- Double down on marketing high-margin products like Copiers & Phones  
- Reevaluate pricing/discount strategy for Furniture items losing money  
- Optimize shipping operations in the Central region  
- Use city-level profit data to focus local campaigns

---

## 💡 Learnings & Takeaways

- Practiced full analytics pipeline: data cleaning ➝ EDA ➝ dashboarding  
- Gained beginner-to-intermediate proficiency in Power BI  
- Learned to translate data into actionable business recommendations  

---

## 📬 Contact

Feel free to connect on [LinkedIn](https://www.linkedin.com/) or drop an issue here if you'd like to collaborate or ask questions!

