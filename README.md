# 📊 Gold Trade Analysis: Egypt & Burkina Faso (2018–2024)

This repository contains the Exploratory Data Analysis (EDA) of gold trade data involving Egypt and Burkina Faso from 2018 to 2024. The project aims to uncover trade patterns, key product flows, partner countries, and value trends over time.

---

## 📁 Files in This Repository

| File Name                       | Description                                             |
|--------------------------------|---------------------------------------------------------|
| cleaned_trade_data.csv       | Cleaned dataset used for analysis                      |
| Exploratory_Data_Analysis(Gold_Trade).docx   | Word document summarizing the full EDA                |
| EDA PART README.md                    | This project overview file                             |

---

## 🔍 Exploratory Data Analysis Summary

### ✅ Dataset Overview

- *Rows*: 524
- *Columns*: 47
- *Date Range*: 2018–2024
- *Countries*: Egypt (314 entries), Burkina Faso (210 entries)
- *Trade Flow*: Export (343), Import (181)

---

### 📦 Product Focus

- *Gold (unwrought, semi-manufactured, powder)* is the main commodity.
- Top product:
  - Gold (including gold plated with platinum) unwrought or in semi-manufactured forms: 258 entries

---

### 🌍 Partner Countries (Top 5)

1. Canada – 255 entries  
2. India – 88  
3. Italy – 70  
4. Germany – 25  
5. France – 24  

---

### 💰 Trade Value (Primary)

- *Mean*: $19.9 million  
- *Max*: $110.7 million  
- *Median*: $3.59 million  
- *Std Dev*: $26.8 million  

---

### 📈 Yearly Trade Value Trend

| Year | Total Trade Value (USD)    |
|------|-----------------------------|
| 2018 | $973 million                |
| 2019 | $2.46 billion               |
| 2020 | $1.88 billion               |
| 2021 | $2.25 billion               |
| 2022 | $1.80 billion               |
| 2023 | $939 million                |
| 2024 | $171 million                |

📊 ![Total Trade Value by Year](total_trade_value_by_year.png)

---
## 📈 Visual Analysis

### 🧪 Boxplot of Primary Trade Value

This chart shows outliers in the trade data. Large values are valid gold exports and are retained.

![Boxplot](boxplot_primaryvalue.png)

---

### 📉 Histogram of Primary Trade Value

Trade values are right-skewed, with many smaller transactions and a few large exports.

![Histogram](histogram_primaryvalue.png)

---

### 🌍 Top 5 Partner Countries by Trade Value

Canada dominates gold trade, followed by India and Italy.

![Top Partners](barplot_top_partners.png)
## ⚠ Data Quality Notes

- Missing values only in altqtyunitabbr (~60% missing)
- No duplicate entries detected
- Categorical values are clean and consistent
- Outliers detected in trade values but reflect real-world scenarios

---

## 🔍 Correlation Analysis

- *Highly correlated*: primaryvalue, fobvalue, netwgt, and qty (0.97–0.99)
- *Negatively correlated*: cifvalue with others (-0.28 to -0.34)

---

## 📌 Insights

- Egypt contributes over *$6.52 billion* in total trade value
- Burkina Faso contributes around *$3.96 billion*
- Canada is the most frequent trade partner
- Gold (in various forms) dominates the product category

---

## 🔮 Next Steps

- Predictive modeling of trade values
- Interactive dashboards in Power BI
- Further analysis on value types (CIF, FOB, Net Weight)

---

## 👤 Author

*BITLA SRAVAN*  
📧 Sravannetha000111@gmail.com  


---

