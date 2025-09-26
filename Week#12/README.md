# California Housing Data Analysis 🏡

This repository contains an exploratory data analysis (EDA) and preprocessing pipeline on the **California Housing dataset**, inspired by the *Hands-On Machine Learning* book.  

The notebook walks through loading the dataset, cleaning, handling missing values, visualizing distributions, detecting/removing outliers, and preparing the data for further machine learning tasks.

---

## 🚀 Features
- Load California housing dataset directly from Géron’s GitHub repo  
- Perform **data inspection** (`head`, `info`, `describe`)  
- Visualize distributions using **Matplotlib, Seaborn, Plotly**  
- Handle missing values  
- **Detect and remove outliers** using IQR method  
- Feature engineering (e.g., `rooms_per_household`, `bedrooms_per_room`, etc.)  
- Ready-to-use cleaned dataset for further ML models  

---

## 🛠️ Installation
Clone the repo and install dependencies:


git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt

Requirements

Python 3.8+

Jupyter Notebook

pandas

numpy

matplotlib

seaborn

plotly

You can install them with:

pip install pandas numpy matplotlib seaborn plotly jupyter

## 📊 Dataset

The dataset is the California Housing Prices dataset:

Source: Hands-On Machine Learning 2nd Edition Datasets

Format: CSV

Columns: longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value, ocean_proximity

## ▶️ Usage

Run the notebook step by step:

jupyter notebook ML_test01.ipynb


You can explore:

Distribution of features

Missing value handling

Outlier detection & removal

Feature engineering

## 📈 Example Visualizations

Histograms of housing features

Boxplots for outlier analysis

Interactive scatter plots with Plotly

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.
