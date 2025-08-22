# COVID-19 Global Data Analysis (2024)

This project analyzes the **WHO COVID-19 global daily dataset** to explore trends in cases, deaths, and recoveries across countries, regions, and seasons. Visualizations are created using **Python**, **Pandas**, **Seaborn**, and **Plotly**.

---

## 📂 Dataset

- Source: [WHO COVID-19 Global Daily Data](https://srhdpeuwpubsa.blob.core.windows.net/whdh/COVID/WHO-COVID-19-global-daily-data.csv)  
- Format: CSV  
- Key columns:
  - `date_reported`: Date of report
  - `country`: Country name
  - `country_code`: ISO3 country code
  - `new_cases`, `cumulative_cases`
  - `new_deaths`, `cumulative_deaths`
  - `who_region`: WHO region

---

## 🧰 Tools & Libraries

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Plotly Express & Graph Objects  
- pycountry (for ISO3 country codes)  

---

## 🔍 Features & Analysis

1. **Data Cleaning & Preprocessing**
   - Handle missing values (`NaN`) and negative values.
   - Extract `year`, `month`, `month_year`, and `season`.

2. **Exploratory Data Analysis (EDA)**
   - Trend analysis for cumulative cases and deaths over time.
   - Top 10 countries by cumulative cases in 2024.
   - Seasonal and regional analysis using WHO regions.

3. **Visualizations**
   - Line plots for cumulative cases and deaths.
   - Bar plots for seasonal totals by region.
   - Choropleth map for cumulative cases worldwide.
   - Histograms for monthly trends and estimated recoveries.

4. **Custom Functions**
   - `cumulative_cases_country(df, country, Xaxis)`: Plot cumulative cases for a specific country.
   - `cumulative_deaths_country(df, country, Xaxis)`: Plot cumulative deaths for a specific country.

---

## 📊 Insights

- Cases and deaths increase over time, with peaks in Winter and Spring.  
- Top countries (USA, India, Brazil) account for the majority of global cases.  
- Most cases are concentrated in Americas, Europe, and parts of Asia.  
- Seasonal patterns are noticeable, with Winter/Spring having higher cases and deaths.  
- Estimated recoveries are increasing, though not official data.

