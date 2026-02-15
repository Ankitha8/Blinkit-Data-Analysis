# Blinkit-Data-Analysis

# 🛒 Blinkit Sales Data Analysis (Python + Jupyter Notebook)

## 📌 Project Overview
This project analyzes Blinkit grocery sales data using Python, Pandas, Matplotlib, and Seaborn to discover business insights about product performance, outlet performance, and customer preferences.

The objective of this project is to:
- Identify top-selling product categories
- Analyze sales by fat content
- Compare outlet tier performance
- Understand overall sales trends

This project demonstrates skills in data cleaning, exploratory data analysis (EDA), and visualization.

---

## 📊 Dataset Information
The dataset contains **8,523 rows and 12 columns** with the following fields:

- Item Fat Content  
- Item Identifier  
- Item Type  
- Outlet Establishment Year  
- Outlet Identifier  
- Outlet Location Type  
- Outlet Size  
- Outlet Type  
- Item Visibility  
- Item Weight  
- Sales  
- Rating  

---

## 🛠️ Tools & Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Cleaning Steps
- Removed duplicate records  
- Standardized fat content values  
- Checked missing values  
- Verified data types  

Example:
```python
df['Item Fat Content'] = df['Item Fat Content'].replace({
    'LF': 'Low Fat',
    'low fat': 'Low Fat',
    'reg': 'Regular'
})

📈 Analysis Performed
1. Total Sales by Item Type
Fruits & Vegetables and Snack Foods generate the highest revenue.
Seafood and Breakfast items have the lowest sales.

2. Sales by Fat Content
Low Fat items contribute about 65% of total sales.
Customers prefer healthier options.

3. Outlet Tier vs Fat Content Sales
Tier 3 outlets generate the highest sales.
Low Fat products dominate across all outlet tiers.

4. Overall Sales Insights
Fruits & Vegetables are the top-performing category.
Snack Foods are consistently high sellers.

Tier 3 outlets perform best in revenue generation.

💡 Future Improvements

Create Power BI Dashboard

Add Machine Learning sales prediction model

Perform customer segmentation analysis
