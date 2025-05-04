# 📈 Sales Data Analysis (2019–2024)

This project delivers a comprehensive, end-to-end analysis of **Amazon-like e-commerce sales data** spanning from **2019 to 2024**. This is a Python-based data analytics project focused on exploring retail sales data to uncover actionable business insights. Using Jupyter Notebook, this project walks through the full data analysis pipeline — from raw data processing to insight-driven visualizations — simulating real-world business questions and solutions.

---

## 📂 Dataset Summary

This project uses a structured sales dataset that mimics real-world e-commerce transactions.

* 🧾 **Total Records**: 5,000 sales transactions
* 📅 **Time Frame**: 2019 to 2024
* 🌍 **Geography**: Multiple global regions and cities
* 🛍️ **Key Fields**:

  * Product Category
  * Region & City
  * Quantity Sold
  * Unit Price
  * Discount
  * Total Sales
  * Profit & Profit Margin
  * Order Date & Status
  * Salesperson

---

## 🎯 Objectives

The primary goals of this sales data analysis project are to:

* 🧹 **Clean and preprocess** raw sales data for structured analysis
* 📊 **Analyze sales performance** by product category, region, and time period
* 📈 **Identify trends** in revenue, profit, and customer behavior
* 🕵️‍♂️ **Answer key business questions** through data-driven exploration
* 🖼️ **Create visual dashboards** to communicate insights effectively
* 💡 **Generate actionable insights** for improving sales strategy and operations

---

## 🧰 Tools & Libraries Used

* **Python 3**
* **Pandas** – for data manipulation
* **NumPy** – for numerical operations
* **Matplotlib & Seaborn** – for data visualization
* **Jupyter Notebook** – for an interactive data analysis workflow
  
---

## 🔍 Exploratory Data Analysis (EDA)

The analysis answers several key business questions:

* 📅 **What was the best month for sales, and how much was earned?**
  → Identifies high-performing months using monthly revenue trends.

* 🌆 **Which cities had the highest number of sales?**
  → Reveals top geographical markets based on order volume.

* ⏰ **What time should advertisements be displayed to maximize effectiveness?**
  → Uses hourly purchase patterns to recommend optimal ad timing.

* 🛍️ **What products are most frequently bought together?**
  → Detects product bundles from orders with matching IDs.

* 📦 **What product sold the most and why?**
  → Combines quantity sold and pricing to explain product demand.

  ---
  
## 📊 Visualizations

This project includes a variety of clear, insight-driven visualizations:

* 📍 **Bar Chart** – Total Sales & Profit by Region
* 📆 **Line Plot** – Monthly Sales Trend (2019–2024)
* 🎯 **Scatter Plot** – Discount vs. Profit Margin by Product Category
* 🧑‍💼 **Bar Chart** – Top 5 Salespersons by Total Sales
* 🥧 **Pie Chart** – Profit Distribution by Order Status

---

## 📎 Output Includes

| Output Type                    | Description                                                             |
| ------------------------------ | ----------------------------------------------------------------------- |
| ✅ **Cleaned Dataset**          | Raw sales data processed and transformed for analysis                   |
| 📈 **Sales & Profit Charts**   | Bar charts comparing sales and profit across regions and top performers |
| 🗓️ **Time-Series Trend**      | Monthly sales trends from 2019–2024 to spot seasonality                 |
| 📉 **Profitability Analysis**  | Scatter plot showing the effect of discounts on profit margins          |
| 🧑‍💼 **Performance Insights** | Top 5 salespersons ranked by total sales                                |
| 🥧 **Order Status Breakdown**  | Pie chart showing profit distribution across order statuses             |
| 📊 **Visual Dashboards**       | A collection of data visualizations rendered using Seaborn & Matplotlib |
| 📂 **Exported Excel Files**    | Both raw and cleaned data available for reuse or BI integration         |

---

## ✅ Future Work

* 📊 Predictive modeling for sales forecasting
* 🧑‍🤝‍🧑 Customer segmentation
* 🌐 Integration with real-time data streams

---
## 📊 Key Sales Insights & Visualizations (2019–2024)

### 📊 **1. Total Sales and Profit by Region (Bar Chart)**

**🎯 Purpose:**
To compare **total revenue** and **profit margin** across different geographic regions.

**🔍 Insight:**
Identifies the most profitable regions. From the chart, **South America**, **North America**, and **Asia** likely stand out as top contributors in both **sales** and **profit**.

**📊 Visualization Details:**

* **Chart Type:** Bar Chart
* **X-axis:** Region names
* **Y-axis:** Sales and Profit in USD
* **Color Palette:** `'deep'` (dual-colored bars for comparison)
* **Features:** Labels, rotated x-axis ticks for readability, and a clear title

---

### 📈 **2. Monthly Sales Trend (Line Plot)**

**🎯 Purpose:**
To visualize **sales performance trends** on a monthly basis from 2019 to 2024.

**🔍 Insight:**
The chart shows **seasonality**, with visible **spikes and dips** indicating high and low performing months. This can help optimize inventory and marketing efforts.

**📊 Visualization Details:**

* **Chart Type:** Line Plot (Time-Series)
* **X-axis:** Monthly periods (`Order Date` by month)
* **Y-axis:** Total Sales in USD
* **Features:** Rotated x-axis labels, labeled axes, and a plot title

### 🎯 **3. Discount vs Profit Margin (Scatter Plot)**

**🎯 Purpose:**
To assess the **impact of discount levels** on **profit margins**, and see how this relationship varies across product categories.

**🔍 Insight:**

* Discounts tend to correlate negatively with profit margin — **higher discounts often reduce profitability**.
* Different **product categories react differently**, highlighting the need for category-specific discount strategies.

**📉 Visualization Details:**

* **Chart Type:** Scatter Plot
* **X-axis:** Discount (%)
* **Y-axis:** Profit Margin
* **Hue (Color):** Product Category
* **Color Palette:** `'coolwarm'`
* **Features:** Title included for context, and each point is category-labeled via legend

---

### 🧑‍💼 **4. Top 5 Salespersons by Total Sales (Bar Chart)**

**🎯 Purpose:**
To highlight the **top-performing sales team members** by revenue generated.

**🔍 Insight:**

* The chart ranks salespeople, clearly showing who drives the most sales.
* Useful for **performance reviews**, **recognition programs**, or **incentive planning**.

**📊 Visualization Details:**

* **Chart Type:** Bar Chart
* **X-axis:** Salesperson Names
* **Y-axis:** Total Sales (USD)
* **Color Palette:** `'rocket'`
* **Features:** Sorted bars, labeled y-axis, and a professional layout

---

### 📎 **5. Profit Distribution by Order Status (Pie Chart)**

**🎯 Purpose:**
To understand how **profit is distributed** across different **order statuses** (e.g., Completed, Returned, Canceled).

**🔍 Insight:**

* Shows what proportion of total profit comes from completed vs. non-completed orders.
* Can help detect operational inefficiencies (e.g., returns affecting margins).

**🥧 Visualization Details:**

* **Chart Type:** Pie Chart
* **Color Palette:** `'rainbow'`
* **Labels:** Each segment shows percentage contribution
* **Y-axis:** Removed for a cleaner look

---

## 📥 Files Included

| File                                      | Description                                        |
| ----------------------------------------- | -------------------------------------------------- |
| `Sales Data Analysis.ipynb`               | Main Jupyter notebook containing the full analysis |
| `amazon_sales_dataset_2019_2024.xlsx`     | Original dataset file                              |
| `cleaned_sales_data.csv`                  | Cleaned dataset after preprocessing                |

