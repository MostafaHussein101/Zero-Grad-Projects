# 🚢 Titanic Survival Analysis – Exploratory Data Analysis (EDA)

This project explores the **Titanic dataset** to uncover patterns in passenger survival rates.  
Through data cleaning, feature engineering, and visualization, we aim to identify the factors most strongly associated with survival.

---

## 📂 Project Overview
The Titanic dataset is a well-known dataset used for classification and pattern-finding exercises.  
In this analysis, we:

- Handle missing data through **imputation** (e.g., `Embarked`, `Age`).
- Create a new feature: **`family_size`**.
- Explore survival rates based on **gender**, **age group**, and **family size**.
- Visualize patterns to make insights easier to interpret.

---

## 🛠 Features
- **Missing Value Handling:** Applied mode imputation for `Embarked` and addressed missing ages.
- **Feature Engineering:** Combined `SibSp` and `Parch` into `family_size`.
- **Age Group Categorization:** Grouped passengers based on historical generational cohorts.
- **Correlation Analysis:** Checked relationships between features before imputation.
- **Data Visualization:** Used **Seaborn** and **Matplotlib** for:
  - Missing data heatmap  
  - Correlation heatmap  
  - Survival rate by family size  
  - Survival rate by age group and gender  

---

## 📊 Example Insights
- **Family Size Effect:** Passengers with family sizes of **3**, **2**, or **1** had the highest survival rates.  
- **Gender Impact:** Females had a much higher survival rate than males across most age groups.  
- **Age Group Trends:**
  - Males with the highest survival rate: *Greatest Generation* (1910–1912)  
  - Females with the highest survival rate: *Pre-Victorian* (≤ 1869)  
  - Males with the lowest survival rate: *Lost Generation* (1883–1900)  
  - Females with the lowest survival rate: *Early 20th* (1901–1909)  
