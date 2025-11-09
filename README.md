# 🇩🇪 Germany Renewable Energy Analysis (2015–2020)

This project analyzes Germany’s renewable energy trends from 2015 to 2020 using data from the **Open Power System Data (OPSD)** platform. It focuses on how much of Germany’s electricity comes from **wind and solar power**, how these sources vary by season, and how their share has grown over time.

📖 See [glossary.txt](https://github.com/aakshatha02/Germany-Renewable-Energy-Analysis-2015-2020/blob/main/glossary.txt) for key terms.

---

## 📊 Project Overview

- **Goal:** Explore Germany’s progress in renewable energy generation and identify seasonal and yearly trends.  
- **Data Source:** [Open Power System Data (OPSD)](https://data.open-power-system-data.org/time_series/2020-10-06)  
- **Name of CSV File:** `time_series_60min_singleindex.csv`  
- **Period Covered:** 2015–2020 (latest available in dataset)  
- **Main Question:**  
  > How much of Germany’s power came from renewable sources (wind + solar) over time?

---

## 🧩 Key Analyses

### 1️⃣ Renewable Share Trend (2015–2020)

<div align="center">
  <img width="700" alt="Renewable Share Trend" src="https://github.com/aakshatha02/Germany-Renewable-Energy-Analysis-2015-2020/blob/main/Screenshot/Screenshot1.png">
</div>

- The chart above shows the monthly share of renewable energy in Germany’s electricity generation from 2015 to 2020.  
- In 2015–2016, renewables contributed around 15–30% of total generation. From 2017 onwards, the share became more variable but continued to grow, reaching **over 50%** in early 2020.  
- This increase may be due to favorable weather and reduced electricity demand during early COVID-19 months.  
- The overall trend reflects progress under **Germany’s Energiewende (energy transition)** policy.

---

### 2️⃣ Solar vs Wind Contribution

<div align="center">
  <img width="700" alt="Solar vs Wind Contribution" src="https://github.com/aakshatha02/Germany-Renewable-Energy-Analysis-2015-2020/blob/main/Screenshot/Screenshot2.png">
</div>

- The chart shows monthly contributions of **solar** and **wind** power from 2015–2020.  
- Wind energy consistently provides a larger share of total electricity compared to solar, reflecting Germany’s heavy investment in wind infrastructure.  
- **Solar** generation peaks in summer and drops in winter due to sunlight variation.  
- **Wind** varies throughout the year, especially strong in late 2019–early 2020 during stormy periods.  
- Together, both sources highlight Germany’s shift toward a cleaner, low-carbon grid.

---

### 3️⃣ Seasonal Heatmap

<div align="center">
  <img width="700" alt="Seasonal Heatmap" src="https://github.com/aakshatha02/Germany-Renewable-Energy-Analysis-2015-2020/blob/main/Screenshot/Screenshot3.png">
</div>

- The heatmap shows the **average monthly share of renewable energy** (mainly wind + solar) from 2015–2020.  
- Higher shares occur in **winter and early spring (Feb–Apr)** due to stronger winds, while **summer months** are dominated by solar.  
- Over time, renewable shares increased, surpassing **50% in February 2020**, showing steady progress toward cleaner energy.

---

## 🧠 Insights

- Germany’s renewable energy share **steadily increased** between 2015–2020.  
- **Wind** provides the largest contribution; **solar** shows strong seasonal variation.  
- Dataset ends in **2020**, so more recent trends (2021–2025) aren’t included.  
- Findings highlight Germany’s continued success under **Energiewende** policies.

---

## ✅ Conclusion

This analysis shows that Germany made strong progress in using renewable energy—mainly wind and solar—for its electricity between 2015 and 2020. The share of renewables steadily increased, sometimes going above 50% of total electricity generation. This growth came from steady investment in clean energy and supportive government policies. Clear seasonal patterns appear: wind power is stronger in winter, while solar peaks in summer.

It’s important to note that the dataset ends in 2020, so it does not include more recent trends up to 2025. Future data could show how Germany’s renewable energy share has changed since then, especially with new policies and technologies. Overall, the findings highlight the success of Germany’s Energiewende (energy transition) while showing the need for continued improvements in grid flexibility, energy storage, and reliability as renewables grow further.

---

## ⚙️ Tools Used

- **Python**  
- **Pandas** – for data cleaning and aggregation  
- **Matplotlib** & **Seaborn** – for visualization  

---
