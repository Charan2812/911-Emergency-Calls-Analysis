# 911-Emergency-Calls-Analysis
Data analysis project on 911 emergency calls dataset using Python, NumPy, Pandas, Matplotlib, Seaborn.

## Project Title  
### 911 Emergency Calls Data Analysis using Python

## Description  
This project performs an in-depth exploratory data analysis (EDA) on the **Montgomery County 911 Emergency Call Dataset**.  
The analysis uncovers useful insights such as the busiest townships, most common emergency reasons, call frequencies by time, and daily/weekly/monthly patterns.  
Visualizations are generated using Matplotlib and Seaborn to clearly represent emergency trends and help improve public safety decision-making.

## Tech Stack  
- **Python 3.x**  
- **Pandas** – Data cleaning & manipulation  
- **NumPy** – Numerical computing  
- **Matplotlib** – Data visualization  
- **Seaborn** – Advanced visualizations  
- **Jupyter Notebook** – Code execution & analysis environment  

## Data Source  
The dataset used in this project is downloaded from **Kaggle**:  
- **Dataset Name:** 911 Calls – Montgomery County, PA  
- **File Used:** `Emergency_Calls.csv`  
- Contains latitude, longitude, description, timestamps, township details, and emergency title

## Features / Highlights  

### 1.Data Exploration
- Displays dataset structure — number of rows, columns, and datatypes.  
- Identifies missing values and unique counts in fields like township and title codes.

### 2.Township-Level Analysis
- Finds the **top 5 townships** with the highest emergency calls.  
- Identifies which township receives the most emergency calls overall.

### 3.Reason & Title Breakdown
- Extracts new features:  
  - **Reason** (EMS, Fire, Traffic)  
  - **Code** (specific emergency detail)  
- Visualizes the frequency of reasons using count plots.

### 4.Time-Series Analysis
- Converts timestamps into **day, month, year, hour, and weekday**.  
- Analyzes call volume patterns across:  
  - Hours of the day  
  - Days of the week  
  - Months of the year  

### 5.Heatmap & Trend Visualization
- Shows peak call hours using a heatmap.  
- Uses `lmplot` to fit a trend line over monthly call volumes.  
- Line charts showing daily call trends for **EMS**, **Fire**, and **Traffic**.

### 6.Insights for Emergency Services
- Helps identify busy hours and days.  
- Supports planning, staffing, and resource allocation for emergency departments.
# Screenshots
## Countplot
![Countplot](https://github.com/Charan2812/911-Emergency-Calls-Analysis/blob/main/countplot_reason.png)
## Heatmap
![Heatmap](https://github.com/Charan2812/911-Emergency-Calls-Analysis/blob/main/heatmap_day_hour.png)
## Line Chart
![Line Chart](https://github.com/Charan2812/911-Emergency-Calls-Analysis/blob/main/daily_trends_traffic_Ems_fire.png)
## Countplot Day_Reason
![Countplot Day_Reason](https://github.com/Charan2812/911-Emergency-Calls-Analysis/blob/main/day_reason_countplot.png)
## Countplot Day_Reason
![Countplot Month_reason](https://github.com/Charan2812/911-Emergency-Calls-Analysis/blob/main/month_reason_countplot.png)

