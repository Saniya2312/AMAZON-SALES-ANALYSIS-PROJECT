# Amazon Sales Analysis Project

## Overview
This project analyzes Amazon sales data to extract actionable insights on order patterns, product performance, and regional trends. The dataset includes 128,976 records with features like `Order ID`, `Date`, `Status`, `Category`, `Size`, and `Amount`.

## Tools Used
- **Python Libraries**: Pandas, NumPy, Seaborn, Matplotlib
- **Data Handling**: CSV import, cleaning, transformation

## 📊 Key Features
- Data cleaning & preprocessing of sales CSV file
- Exploratory Data Analysis (EDA)
- Visualizations for category-wise, region-wise, and monthly trends
- Insight into top-performing products and shipping behaviors

## Key Steps
1. **Data Loading & Inspection**: 
   - Loaded the dataset and examined structure (`head`, `tail`, `shape`).
2. **Data Cleaning**:
   - Dropped irrelevant columns (`New`, `PendingS`).
   - Handled missing values (`currency`, `Amount`, `ship-city`).
   - Converted `ship-postal-code` to integer and `Date` to datetime.
3. **Exploratory Analysis**:
   - Descriptive statistics (e.g., mean order amount: ₹647).
   - Visualized product size distribution (size "M" most frequent).
4. **Insights**:
   - Top categories: T-shirts and Shirts.
   - High sales volume in Maharashtra (India).
   - Most orders fulfilled via "Standard" shipping.

## 🧠 Skills Demonstrated
- Data Wrangling
- Data Visualization
- Analytical Thinking
- Business Insight Generation

## 📁 Dataset
The dataset used is named `Amazon Sale Report.csv` which includes details like Order Date, Product, Category, Shipping Cost, and Profit.


## 🔗 Project Preview
- Visual insights using line charts, bar graphs, and heatmaps
- Highlighting anomalies and business opportunities
