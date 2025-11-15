# 🎮 Video Game Sales Dashboard (1980–2020)

An interactive and automated dashboard built using Power BI to analyze global video game sales across regions, genres, and platforms.

---

## 📌 Project Overview

This project provides a complete **EDA and visualization of video game sales data** using a modern, dark-themed Power BI dashboard.

Key insights include:
- Global and region-wise sales trends
- Publisher and genre performance
- Team and title distributions
- Year-over-year growth patterns

---

## 📊 Features

- 📅 **Time Range**: 1980 – 2020  
- 🌍 **Sales Distribution**: NA, EU, JP, Other regions  
- 🕹️ **Genres Analyzed**: Action, Sports, Role-Playing, etc.  
- 🏢 **Publishers**: 567 unique publishers  
- 📈 **Dynamic Filters** for Genre, Platform, and Year  
- 📑 **KPIs Displayed**: Platform count, Publisher count, Global sales trend

---

## 🖼️ Preview

![Dashboard Preview](https://github.com/profitter261/Video-Games-Sale-analysis-/blob/main/Screenshot%202025-08-02%20192201.png)

---

## 🔧 Tools Used

- **Power BI** – For building dynamic dashboards
- **Python (Pandas, NumPy)** – For data cleaning and preprocessing
- **Excel/CSV** – Data wrangling and initial formatting

---

## 🧹 Data Cleaning Steps (Python)

- Removed duplicates
- Imputed missing values (e.g., mean for missing years)
- Normalized categorical fields (`genre`, `publisher`)
- Converted 'K' to numerical context (e.g., 1K → 1000)

---

## 📁 Dataset

- Games Dataset: [https://github.com/profitter261/Video-Games-Sale-analysis-/blob/main/Datasets/games.csv]
- Vgsales Dataset: [https://github.com/profitter261/Video-Games-Sale-analysis-/blob/main/Datasets/vgsales.csv]  
- Cleaned and preprocessed before import to Power BI

---

## 🚀 Future Enhancements

- Automate EDA + dashboard using Streamlit
- Add prediction models for future sales
- Convert dashboard to web-based version

---

