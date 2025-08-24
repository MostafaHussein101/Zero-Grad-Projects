# Airbnb NYC EDA

This project explores Airbnb listings in New York City using Exploratory Data Analysis (EDA). The goal is to understand patterns in prices, locations, room types, hosts, and reviews.

---

## 📊 Key Insights

### 1. Listings by Neighbourhood & Room Type
- Most listings are in **Manhattan and Brooklyn**.  
- **Entire home/apt** is the most common type, followed by **Private room**; **Shared room** is rare.  
- Some neighbourhoods mostly have one room type, affecting prices.

### 2. Price Analysis
- Prices vary a lot; there are **very high outliers**.  
- Most listings are under **$1000**, but some reach much higher.  
- **Entire home/apt** is generally more expensive than private or shared rooms.

### 3. Distance from City Center
- Listings closer to **city center (Manhattan)** are usually **more expensive**.  
- There is an **inverse relationship**: farther listings are cheaper.

### 4. Host Analysis
- Most hosts have **1 listing**, while some professional hosts have **many listings**.  
- More listings do not always mean higher reviews.  
- `calculated_host_listings_count` indicates host experience/size.

### 5. Reviews
- `reviews_per_month` and `last_review` show host activity.  
- Active listings often have **higher prices**, but not always.  
- Some listings have **no reviews**, especially new ones.

### 6. Correlation
- Numerical features (`price`, `minimum_nights`, `number_of_reviews`, `reviews_per_month`, `calculated_host_listings_count`) show **weak to moderate correlation**.  
- Price is more influenced by **room type** and **neighbourhood group** than numerical features.

---

## 📈 Visualizations
- Histograms and boxplots for **price distribution by room type and neighbourhood**.  
- Scatter plots showing **price vs distance from city center**.  
- Line plots for **average reviews per host by number of listings**.  
- Maps showing listing locations and distance from city center.

---

## 📌 Conclusion
The EDA shows that **location, room type, and host experience** are key factors affecting Airbnb prices in NYC. Outliers exist, and distance from Manhattan significantly impacts pricing.

---

## 🛠️ Tools
- Python, Pandas, NumPy  
- Seaborn, Plotly, Folium  
- Jupyter Notebook / Kaggle Notebook
