# 🎮 Game Sales Analysis

## 📊 Overview
This project analyzes video game sales data to identify trends in consoles, genres, and global market performance using Python.

---

## 🧹 Data Cleaning
- Selected relevant columns for analysis
- Removed rows with missing sales data
- Created a separate dataset for critic score analysis
- Converted release dates and extracted year

---

## 📈 Key Insights

### 🎮 Console Performance
- Older consoles such as PS2, Xbox 360, and PS3 dominate total sales due to longer market presence
- However, average sales per game show that older systems like GBC and NES have higher-performing titles

### 📅 Sales Trends
- Game sales increased significantly from 2008 and peaked around 2014
- A decline in sales is observed after 2014

### 🎯 Genre Trends
- Action and Sports genres generate the highest total sales

### 🌍 Regional Insights
- North America is the largest market for video game sales

### ⭐ Critic Score Impact
- Weak positive correlation (~0.32) between critic scores and total sales
- Reviews influence sales, but are not the main driver

---

## 📊 Visualizations
The project includes:
- Bar charts (console and genre sales)
- Line chart (sales over time)
- Scatter plot (critic score vs sales)

---

## ⚠️ Limitations
- Dataset reduced after handling missing values
- Analysis based only on games with complete data
- Results may not fully represent the entire gaming market

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib

---

## 📂 Project Files
- `game_sales_analysis.ipynb` – main analysis notebook
