# COVID-19 Explorattory data analysis and Plotly based visualization

##  Objective
To analyze the global spread of COVID-19 using publicly available datasets, perform exploratory data analysis (EDA), and create **interactive visualizations** that highlight pandemic trends across countries and time.

---

##  Dataset
- **covid.csv** and **covid_grouped.csv** from Kaggle/UCI-style repositories.  
- **Size:** 100k+ records across **20+ features**.  
- **Features:** Cases, Deaths, Recoveries, Country/Region, Date.  

---

##  Key Questions
1. How did **COVID-19 cases, deaths, and recoveries** evolve over time?  
2. Which **countries/regions** were most affected during the pandemic?  
3. What differences exist between **daily vs. cumulative trends**?  
4. How can **interactive visualization** help in understanding spread patterns?  

---

##  Analysis & Methods
- **Data Cleaning & Preprocessing**
  - Dropped irrelevant fields (`NewCases`, `NewDeaths`, `NewRecovered`).  
  - Inspected shape, size, missing values, and column types.  
  - Retained structured dataset for visualization (≈100k rows, 20+ columns).  

- **Exploratory Data Analysis**
  - Generated **summary statistics** and random samples for inspection.  
  - Built tabular views using Plotly’s `create_table`.  

- **Data Visualization with Plotly Express**
  - **Time-series plots**: Tracked cases, deaths, recoveries over time.  
  - **Choropleth maps**: Visualized global spread geographically.  
  - **Bar plots**: Compared countries by case count and death toll.  
  - **Scatter plots**: Analyzed trends between daily and cumulative data.  

---

## Results & Insights
- **Pandemic Growth Trends**: Clear peaks in **daily cases** aligned with major outbreak waves.  
- **Regional Hotspots**: Certain countries showed **disproportionately high cases & deaths** compared to others.  
- **Cumulative vs. Daily Analysis**: Daily spikes revealed short-term outbreak intensity, while cumulative counts captured **long-term impact**.  
- **Interactive Dashboards**: Allowed dynamic exploration, enabling users to filter and compare trends across countries.  

---

##  Key Highlights
- **Analyzed 100k+ records** of COVID-19 data across **20+ features**.  
- **Built interactive dashboards** with Plotly for intuitive exploration.  
- **Highlighted pandemic spread** with time-series, choropleths, and bar plots.  
- Delivered **clear storytelling** of outbreak patterns and regional differences.  

---

##  Tools & Libraries
- **Pandas** – Data cleaning & preprocessing  
- **Plotly Express** – Interactive visualization  
- **Matplotlib** – Supporting plots  
- **Python** – Core scripting  

---

## Conclusion
This project demonstrates how **interactive data visualization** can turn raw COVID-19 data into actionable insights, uncovering **temporal trends, geographical hotspots, and case progression** in a user-friendly manner.

---
