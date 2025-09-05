# 🏡 Airbnb Data Analysis with Python  

## 📌 Project Overview  
This project analyzes Airbnb listing data to uncover insights into pricing, availability, and customer behavior. Using Python libraries such as **pandas, matplotlib, and seaborn**, the dataset was cleaned, explored, and visualized to identify patterns that can help hosts and businesses make informed decisions.  

---

## 🎯 Objectives  
- Explore and clean raw Airbnb data.  
- Identify missing values and duplicates.  
- Perform **EDA (Exploratory Data Analysis)** on price, location, reviews, and availability.  
- Visualize correlations between key features (price, beds, reviews, location).  
- Generate actionable insights for business decision-making.  

---

## 🛠️ Tools & Technologies  
- **Python** 🐍  
- **pandas** → data cleaning & manipulation  
- **Matplotlib & Seaborn** → visualizations  
- **Jupyter Notebook** → interactive analysis  

---

## 📂 Workflow  

### 1. Data Loading  
- Loaded Airbnb dataset using `pandas.read_csv()`  
- Checked dataset size, column names, and data types  

### 2. Data Cleaning  
- Handled **missing values** using `isnull().sum()`  
- Dropped duplicates with `drop_duplicates()`  
- Renamed columns for clarity  

### 3. Exploratory Data Analysis (EDA)  
- Distribution of prices, availability, and reviews  
- Top neighborhoods and listings by frequency  
- Correlation analysis between numeric variables  

### 4. Visualizations  
- **Histograms** → price distribution  
- **Bar charts** → top neighborhoods  
- **Heatmap** → correlation of numerical features (`price`, `beds`, `reviews`, etc.)  

### 5. Key Insights  
- Some neighborhoods have significantly higher average prices.  
- Listings with more reviews tend to have lower prices (possible competition effect).  
- Availability is highly skewed; many listings are available only for short durations.  
- Correlation heatmap shows moderate relationships between **beds, price, and availability**.  

---

## 📊 Sample Visualizations  

### 🔹 Price Distribution  
![Price Histogram](https://github.com/AnuragChavan123/Data-Analysis-using-Python/blob/main/Price%20Distribution.png)  

### 🔹 Correlation Heatmap  
![Heatmap](https://github.com/AnuragChavan123/Data-Analysis-using-Python/blob/main/Heatmap.png)  

---

## 🚀 Results (STAR Method)  
- **Situation:** Airbnb dataset with raw, unstructured listing data.  
- **Task:** Clean and analyze the dataset to extract meaningful insights.  
- **Action:** Applied pandas for cleaning, matplotlib/seaborn for visualization, and correlation analysis.  
- **Result:** Produced a clear dashboard of insights that highlight pricing trends, neighborhood dynamics, and customer behavior — helping stakeholders understand factors that influence Airbnb bookings.  

---

## 📁 Project Structure  
```
Airbnb-Data-Analysis/
│── Airbnb Python Project.ipynb   # Jupyter Notebook with code
│── data/                         # Dataset (CSV file)
│── images/                       # Saved plots & visualizations
│── README.md                     # Project documentation
```

---

## 📌 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/airbnb-python-project.git
   cd airbnb-python-project
   ```
2. Install dependencies  
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Open Jupyter Notebook  
   ```bash
   jupyter notebook "Airbnb Python Project.ipynb"
   ```

---

## 🔮 Future Improvements  
- Add **geospatial visualizations** (map-based insights with Folium/Plotly).  
- Automate data pipeline for updated Airbnb datasets.  
- Build a predictive model for price recommendation.  

---

## 🙌 Acknowledgements  
- Dataset: Airbnb public dataset (InsideAirbnb).  
- Libraries: pandas, matplotlib, seaborn.  
