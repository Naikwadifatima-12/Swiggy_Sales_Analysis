# Swiggy-Sales-Analysis (Data Analysis using Python)

## Project Objective
To analyze Swiggy sales data to uncover revenue trends, customer preferences, and performance across cities, states, and food categories. So that, business stakeholders can make data-driven decisions to boost sales and improve customer satisfaction.

## Dataset used
- <a href="https://github.com/Naikwadifatima-12/Swiggy_Sales_Analysis/blob/main/swiggy_data.xlsx">Dataset</a>

## Libraries Used
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
```

## Questions (KPIs)
- What is the Total Sales (INR)?
- What is the Average Rating across all orders?
- What is the Average Order Value (INR)?
- What is the total Ratings Count?
- What is the Total Number of Orders?
- Which month got the highest sales? (Monthly Sales Trend)
- Which day of the week generates the most revenue? (Daily Sales Trend)
- What is the revenue split between Veg vs Non-Veg food?
- Which states contribute the most to total sales?
- What is the Quarterly Performance Summary (Sales, Rating, Orders)?
- Which are the Top 5 Cities by Sales?
- Dashboard Interaction <a href="https://github.com/Naikwadifatima-12/Swiggy_Sales_Analysis/blob/main/Swiggy_project.ipynb">View Notebook</a>

## Process
- Loaded the dataset from Excel and performed initial exploration using `df.head()`, `df.info()`, and `df.describe()`.
- Verified data for any missing values and anomalies, and sorted out the same.
- Made sure data is consistent and clean with respect to data type, data format and values used.
- Engineered new features: `YearMonth`, `DayName`, `Quarter`, and `Food Category` (Veg/Non-Veg classification using keyword matching).
- Computed KPIs: Total Sales, Average Rating, Average Order Value, Ratings Count, and Total Orders.
- Created charts using Matplotlib, Seaborn, and Plotly to answer each business question.

## Dashboard
![Swiggy Analysis Dashboard](#)

## Project Insight
- **Monthly trend** reveals peak revenue months, helping plan promotional campaigns around high-demand periods.
- **Weekday analysis** shows which days drive the most revenue, enabling targeted day-specific offers.
- **Veg vs Non-Veg** revenue split highlights dominant food preferences among customers on the platform.
- **State-wise analysis** identifies top-performing states for regional marketing focus.
- **Top 5 Cities** by sales pinpoint the highest-value urban markets for business expansion.
- **Quarterly summary** tracks Sales, Average Rating, and Order Count across Q1–Q4 for performance benchmarking.

## Final Conclusion:
To improve Swiggy's sales performance, a strategic marketing plan should focus on the **top 5 cities** and **high-revenue states**, especially during **peak months and high-footfall weekdays**. Since food category preferences (Veg vs Non-Veg) vary by region, **personalized menu promotions** tailored to local tastes can significantly increase order volume. Maintaining and improving **customer ratings** through quality and delivery consistency will further drive repeat orders and platform loyalty.

## Tools Used
- **Python** — Pandas, NumPy, Matplotlib, Seaborn, Plotly Express
- **Jupyter Notebook**
