# NYC Motor Vehicle Collision Analysis

## Project Overview

**[View the Complete Python Analysis](NYC_Motor_Vehicle_Collision_Analysis.ipynb)**

This project analyzes motor vehicle collisions across New York City to identify geographic, seasonal, and time-based patterns in crash frequency and severity.

Using publicly available NYC Open Data, our team conducted exploratory data analysis (EDA), logistic regression, and K-means clustering to investigate factors associated with motor vehicle crashes.

## Technologies Used

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, Statsmodels
- **Development Environment:** Google Colab

## Data Sources

The project uses two datasets from NYC Open Data:

- [Motor Vehicle Collisions — Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
- [Motor Vehicle Collisions — Vehicles](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Vehicles/bm4k-52h4)

These datasets were combined using a common collision identifier to examine crash characteristics and vehicle information.

## My Contributions

I was responsible for developing the Python code for the exploratory data analysis portion of the project.

My work included:

- Analyzing crash frequency across NYC ZIP codes.
- Calculating fatal crash rates to compare collision severity across geographic locations.
- Examining crash patterns across different times of day and seasons.
- Creating bar charts and heatmaps using Matplotlib and Seaborn.
- Interpreting findings to identify relationships between crash frequency and severity.

## Key Findings

### 1. Crash Frequency vs. Severity

ZIP codes with the highest crash frequency did not necessarily have the highest fatal crash rates, demonstrating that collision frequency and severity are distinct measures.

### 2. Time-of-Day Patterns

Afternoon periods experienced the highest crash frequency across most seasons, while nighttime crashes exhibited higher fatal crash rates.

### 3. Seasonal Trends

Crash frequency and severity varied across seasons, with elevated crash activity observed during summer months.

## Additional Group Analysis

The project also incorporated logistic regression and K-means clustering to explore factors associated with fatal crashes.

These models were developed as part of the group's broader analysis. Due to class imbalance and other data limitations, the machine learning results should be interpreted as exploratory rather than reliable predictions.

## Project Limitations

- Public datasets are updated regularly, meaning results may change when the notebook is rerun.
- Missing values required additional cleaning and filtering.
- Machine learning analysis used a sample of 10,000 observations due to computational constraints.
- Fatal crashes represented a small proportion of observations, limiting predictive model performance.

## About This Project

This project was completed collaboratively for CIS 3120 at Baruch College, City University of New York.

My primary contribution was the Python-based exploratory data analysis, including statistical calculations, visualizations, and interpretation of collision patterns.
