# COVID-19-India-Data-Analysis-with-visualization
This COVID-19 India Data Analysis with data visualization with matplotlib

# 🦠 COVID-19 India Data Analysis Project

This project analyzes the spread and impact of COVID-19 across Indian states using publicly available data from [https://data.incovid19.org](https://data.incovid19.org). The goal is to extract insights, visualize trends, and practice key data science skills like data cleaning, groupby operations, rolling averages, and plotting.

---

## 📁 Dataset

- **Source**: [states.csv](https://data.incovid19.org/csv/latest/states.csv)  
- **Columns Used**: `Date`, `State`, `Confirmed`, `Recovered`, `Deceased`, `Tested`

---

## ✅ Completed Tasks

### Task 1: Top 5 States by Confirmed COVID-19 Cases  
- Filters the latest date from the dataset  
- Sorts states by total confirmed cases  
- Visualizes the top 5 states using a vertical bar chart with labels  

### Task 2: 7-Day Moving Average of Daily New Confirmed COVID-19 Cases  
- Focuses on 5 major states: Maharashtra, Kerala, Delhi, Tamil Nadu, Karnataka  
- Calculates daily new confirmed cases using `.groupby().diff()`  
- Applies `.rolling(7).mean()` for smoothing  
- Plots trends using multi-line charts to compare the spread  

### Task 3: Top 5 States by COVID-19 Death Rate (%)  
- Calculates death rate = `Deceased / Confirmed`  
- Sorts and filters top 5 states by highest death percentage  
- Displays data in a horizontal bar chart with percentage labels  

---

## 📊 Skills Practiced

- Data Cleaning with Pandas  
- GroupBy and Aggregation  
- Date Handling with `pd.to_datetime()`  
- `.diff()`, `.rolling().mean()`, `.transform()`  
- Data Visualization with Matplotlib  
- Formatting and Annotating Charts  

---

## 🚀 How to Use

1. Load the dataset using Pandas  
2. Follow each task step-by-step in your notebook or script  
3. Run the plots to visualize results  
4. Experiment by adding more states, metrics, or time periods  

---

## 📌 Next Possible Tasks

- Task 4: Identify the day with the highest daily spike per state  
- Task 5: Compare recovery rates across states  
- Task 6: Create an interactive dashboard (Plotly / Streamlit)  

---

## 🧠 Author

**Adarsh Kumar**

