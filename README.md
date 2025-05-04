# Sales Data Analysis

**Sales Data Analysis** is a Python-based data analytics project focused on exploring retail sales data to uncover actionable business insights. Using Jupyter Notebook, this project walks through the full data analysis pipeline — from raw data processing to insight-driven visualizations — simulating real-world business questions and solutions.

## 🧹 Data Preparation

The dataset is composed of multiple CSV files representing monthly sales from a retail store. The notebook:

* Merges 12 months of sales data into a single dataset.
* Cleans missing and incorrect values (e.g., NaNs, corrupt rows).
* Converts columns to appropriate data types.
* Creates new columns for deeper analysis, including:
  * **Month** (extracted from `Order Date`)
  * **Sales** (calculated from quantity and price)
  * **City** (parsed from customer address)
  * **Hour** (for time-based analysis)

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

## 📊 Visualizations

The notebook includes various visualizations for better insight delivery:

* Bar charts (e.g., monthly and city sales)
* Line plots (e.g., sales by hour)
* Heatmaps (e.g., time-based trends)
* Scatter plots (e.g., price vs. quantity sold)

## 🧰 Tools & Libraries Used

* **Python 3**
* **Pandas** – for data manipulation
* **NumPy** – for numerical operations
* **Matplotlib & Seaborn** – for data visualization
* **Jupyter Notebook** – for an interactive data analysis workflow

## 📌 Business Impact

This project simulates how data analytics can help businesses:

* Identify high-performing timeframes and locations.
* Optimize advertising schedules.
* Understand customer purchasing behavior.
* Adjust pricing and inventory strategies based on demand.
