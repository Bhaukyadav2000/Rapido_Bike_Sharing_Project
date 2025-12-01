🚲 Rapid Bike Sharing Analysis & Demand Prediction

📌 Project Overview

The Rapid Bike Sharing Analysis project explores how environmental and
temporal factors affect daily bike rental demand. Using the popular
**Bike Sharing Dataset**, this project performs extensive Exploratory
Data Analysis (EDA) and builds a **Multiple Linear Regression model** to
predict rental counts based on weather, season, and time-based features.

📊 Objectives

-   Understand usage trends and seasonality in bike rentals
-   Identify key factors influencing rental demand
-   Build a predictive model for forecasting daily bike counts
-   Visualize correlations and trends across multiple variables

🗂️ Dataset

-   **Source:** Bike Sharing Dataset (UCI Machine Learning Repository)
-   **File Used:** `day.csv`
-   Features include: `season`, `mnth`, `weekday`, `weathersit`, `temp`,
    `atemp`, `hum`, `windspeed`, `cnt` (target variable)

🧪 Key Steps Performed

1. Data Loading & Cleaning

-   Loaded dataset using pandas
-   Checked datatypes, summary stats, and missing values

2. Exploratory Data Analysis (EDA)

-   Visualized distributions and trends
-   Analyzed rentals across seasons, months, weather, and working days
-   Generated heatmaps and correlation plots

3. Feature Engineering

-   Label encoding categorical variables
-   Train-test split (70/30)

4. Model Building

-   Trained a **Multiple Linear Regression** model
-   Evaluated predictions using R² and Adjusted R²

5. Model Performance

-   **Test R²:** 0.83
-   Strong alignment between actual vs predicted values

📈 Visualizations Included

-   Distribution plots
-   Seasonal and monthly trend charts
-   Correlation heatmap
-   Regression evaluation plots

🧰 Tech Stack

-   Python, Pandas, NumPy
-   Matplotlib, Seaborn
-   Scikit-Learn
-   Jupyter Notebook