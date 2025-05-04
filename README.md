# 📈 Sales Data Analysis (2019–2024)

This project delivers a comprehensive, end-to-end analysis of **Amazon-like e-commerce sales data** spanning from **2019 to 2024**. This is a Python-based data analytics project focused on exploring retail sales data to uncover actionable business insights. Using Jupyter Notebook, this project walks through the full data analysis pipeline — from raw data processing to insight-driven visualizations — simulating real-world business questions and solutions.

---

## 📂 Dataset Summary

* **Records**: 5,000 sales transactions
* **Time Range**: 2019 to 2024
* **Key Fields**:

  * Product Category
  * Region
  * Quantity Sold
  * Unit Price
  * Discount
  * Total Sales
  * Profit Margin

---

## 🔍 Objectives

* Clean and explore raw sales data
* Analyze sales performance by product, time, and geography
* Visualize key business KPIs like revenue and profit
* Identify trends and generate actionable insights

---

## 🧰 Tools & Libraries Used

* **Python 3**
* **Pandas** – for data manipulation
* **NumPy** – for numerical operations
* **Matplotlib & Seaborn** – for data visualization
* **Jupyter Notebook** – for an interactive data analysis workflow
  
---
## 📈 Exploratory Data Analysis (EDA)

The analysis answers several key business questions:

* **What was the best month for sales, and how much was earned?**  
  → Monthly revenue is calculated and visualized using bar charts.

* **Which city had the highest number of sales?**  
  → A city-wise sales distribution helps identify top markets.

* **What time should advertisements be displayed to maximize effectiveness?**  
  → An hourly analysis shows peak times of customer activity.

* **What products are most frequently bought together?**  
  → By analyzing orders with the same ID, frequent product pairings are revealed.

* **What product sold the most and why?**  
  → A price vs. quantity sold analysis helps uncover customer pricing preferences.

  ---
  
## 📊 Visualizations

The notebook includes various visualizations for better insight delivery:

* Bar charts (e.g., monthly and city sales)
* Line plots (e.g., sales by hour)
* Heatmaps (e.g., time-based trends)
* Scatter plots (e.g., price vs. quantity sold)

---

## 📎 Output Includes

* ✅ Tabular summaries
* 📉 Line and bar charts to observe trends
* 📊 Sales distribution plots by category and region
* 🖱️ Interactive visualizations for deeper exploration

---

## ✅ Future Work

* 📊 Predictive modeling for sales forecasting
* 🧑‍🤝‍🧑 Customer segmentation
* 🌐 Integration with real-time data streams

---
## 📊 Key Sales Insights & Visualizations (2019–2024)

## 1. **Total Sales and Profit by Region (Bar Chart)**

### 🎯 **Purpose**

Compare **total revenue** and **profit margin** across various regions.

### 🔍 **Insights**

* Identifies the **most profitable regions**.
* Highlights regions like **South America**, **North America**, and **Asia** as likely leaders in both sales and profit.

### 📊 **Visualization Details**

* **Chart Type**: Bar Chart
* **X-axis**: Regions
* **Y-axis**: Amount in USD
* **Bars**: Dual bars per region (Sales and Profit)
* **Color Palette**: `'deep'`

---

## 2. **Monthly Sales Trend (Line Plot)**

### 🎯 **Purpose**

Track **monthly sales performance** over time from **2019 to 2024**.

### 🔍 **Insights**

* Reveals **seasonal trends** and **growth patterns**.
* Highlights **spikes and dips** that indicate peak and off-peak months.

### 📈 **Visualization Details**

* **Chart Type**: Time-series Line Plot
* **X-axis**: Monthly periods (2019–2024)
* **Y-axis**: Total Sales
* **Style**: Smooth line curve (optional moving average overlay)

---

## 3. **Discount vs Profit Margin (Scatter Plot)**

### 🎯 **Purpose**

Understand the **impact of discounts** on **profitability**.

### 🔍 **Insights**

* Examines whether **higher discounts reduce** profit margins.
* Distinguishes **product category behavior** under discounts.

### 📉 **Visualization Details**

* **Chart Type**: Scatter Plot
* **X-axis**: Discount (%)
* **Y-axis**: Profit Margin
* **Color**: By Product Category using `'coolwarm'` palette
* **Tooltip**: Shows Category, Discount %, and Profit Margin per point

---

## 4. **Top 5 Salespersons by Total Sales (Bar Chart)**

### 🎯 **Purpose**

Recognize **top-performing salespeople**.

### 🔍 **Insights**

* Identifies team members who **generate the most revenue**.
* Valuable for **performance reviews and incentive planning**.

### 📊 **Visualization Details**

* **Chart Type**: Bar Chart
* **X-axis**: Salespersons
* **Y-axis**: Total Sales
* **Color Palette**: `'rocket'`
* **Bars**: Sorted descending by sales value

---

## 📥 Files Included

| File                                      | Description                                        |
| ----------------------------------------- | -------------------------------------------------- |
| `Sales Data Analysis.ipynb`               | Main Jupyter notebook containing the full analysis |
| `amazon_sales_dataset_2019_2024.xlsx`     | Original dataset file                              |
| `cleaned_sales_data.csv`                  | Cleaned dataset after preprocessing                |

