# Electricity Consumption Analysis

## 📌 Project Overview
This project analyzes electricity consumption in Morocco, recorded at **10-minute intervals** across **three zones**. The dataset includes environmental factors such as **temperature, humidity, and wind speed**.

## 🔍 Objectives
- Identify **seasonal patterns** in electricity consumption (hourly, weekly, annual).
- Compare electricity consumption trends across different **zones**.

## 📂 Dataset
- **Source:** UCI Machine Learning Repository
- **Features:**
  - `Datetime`: Timestamp of electricity consumption
  - `PowerConsumption_Zone1`: Consumption in Zone 1 (KwH)
  - `PowerConsumption_Zone2`: Consumption in Zone 2 (KwH)
  - `PowerConsumption_Zone3`: Consumption in Zone 3 (KwH)
  

## 📊 Key Findings
- **Peak consumption** occurs in the evenings, while early mornings see the lowest usage.
- **Different zones show varying patterns**, possibly due to differences in population and industrial activity.

## 📌 Methodology
1. **Data Cleaning**: Converted `Datetime` to `datetime64`, handled missing values.
2. **Feature Engineering**: Extracted **hour**, **day of the week**, and **month**.
3. **Exploratory Data Analysis**: Visualized trends using **line charts, heatmaps**.
4. **Time Series Analysis**: Identified daily and seasonal consumption patterns.
5. **Insights & Conclusion**: Summarized findings for energy optimization.
