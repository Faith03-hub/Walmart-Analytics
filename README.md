# 🛒Walmart Sales Analytics
End-to-End Retail Insights with Python & Power BI

## 📌 Project Overview
This project explores Walmart’s weekly sales data to uncover trends, correlations, and business insights using both Python and Power BI. It demonstrates a full analytics workflow—from raw data cleaning to interactive dashboard storytelling.

## 🧹Data Cleaning (Python)
Using Python, I transformed the raw dataset to meet the following criteria:

Dates converted to MM-DD-YYYY format

Sorted by Store (ascending) and Date (ascending)

Rounded values for clarity:

Weekly_Sales: 2 decimal places

Temperature: nearest whole number

Fuel_Price: 2 decimal places

CPI & Unemployment: 3 decimal places

Verified and handled missing data

The cleaned dataset was exported for use in Power BI.

## 📊  Power BI Dashboard
The dashboard visualizes key metrics and relationships:

Sales Trends Over Time

Holiday vs Non-Holiday Sales

Store-Level Performance

CPI & Fuel Price Correlations

Interactive Filters for date and store

### 💡 Business Questions Explored
Which holidays drive the biggest sales spikes?

Which stores face the highest and lowest unemployment rates—and why?

How does CPI correlate with Weekly Sales, and how does this change during holidays?

What role might Fuel Price play in consumer behavior and sales performance?

## 📁 Project Structure
Walmart-Sales-Analysis

- README.md
- data

    - Walmart_Original.csv
    - Walmart_Cleaned.csv
      
- Walmart.ipynb
- PowerBI_Dashboard
    - Walmart_Sales_Dashboard.pbix
### 🛠 Tools Used
Python: pandas, numpy, matplotlib, seaborn

Power BI: dashboard design, interactive visuals

### 🚀 Next Steps
This project lays the foundation for deeper retail analytics. Future enhancements may include:

Time series forecasting

Store clustering

External economic indicators
