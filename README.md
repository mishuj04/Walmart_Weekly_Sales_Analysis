# 📊 Walmart Sales Analysis – Holiday Impact

This project analyzes Walmart's weekly sales data to understand how holidays affect store performance across the United States. Using Python, we uncover trends, outliers, and make business recommendations.

---

## 🎯 Objectives

- Compare average weekly sales during holidays vs. non-holidays
- Identify stores where holidays have a negative or positive effect
- Find stores that consistently perform well
- Detect outliers and variability in weekly sales

---

## 📁 Dataset

- Dataset Source: [Walmart Store Sales Forecasting](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)
- Columns Used: `Store`, `Date`, `Weekly_Sales`, `Holiday_Flag`, `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`

---

## 🧪 Methodology

- Data Cleaning: Handled missing values, converted `Date` to datetime
- Feature Engineering: Added weekly, monthly aggregations
- Comparative Analysis: Holiday vs. non-holiday weekly sales
- Statistical Measures: Mean, Variance
- Visualization: Bar plots, line graphs, box plot using Matplotlib & Seaborn

---

## 📈 Key Insights

- Most stores show increased sales during holidays.
- Some stores perform worse during holidays.
- Stores are consistently high performers.
- Higher sales variance observed during holiday weeks.

---

## 💼 Business Impact

- Target promotions in high-performing stores during holidays
- Optimize staffing and inventory in underperforming holiday stores
- Replicate strategies from consistently successful stores

---

## ✅ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
