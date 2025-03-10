# Austin Animal Center Intakes - Time Series Forecasting

## Overview
This project analyzes historical animal intake data from the **Austin Animal Center**, using **time series analysis** to uncover trends, seasonality, and forecasting patterns in animal intakes over time.

## Key Features
- **Exploratory Data Analysis (EDA):**
  - Data cleaning and preprocessing.
  - Visualization of intake trends over the years.
  - Identifying seasonal patterns and anomalies.
- **Time Series Modeling:**
  - **Exponential Smoothing Models (ETS)**
  - **Seasonal ARIMA (SARIMA)**
  - **Neural Networks for Time Series (NNETAR)**
- **Forecasting & Evaluation:**
  - Predicted future animal intakes based on historical trends.
  - Evaluated models using **RMSE, MAPE, and residual analysis**.
  - Best model: **ETS(A,N,A)** due to its low error and strong seasonality capture.

## Technologies Used
- **R** (forecast, zoo, ggplot2, tidyverse)
- **R Markdown** for report generation
- **GitHub** for version control

## Results
- **Seasonal Trends:** Animal intakes peak in May and drop towards the end of the year.
- **COVID-19 Impact:** A significant intake drop in 2020 followed by a rising trend.
- **Best Forecasting Model:** ETS(A,N,A) provided the most accurate results.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/austin-animal-intakes.git
   ```
2. Open **RStudio** and install required libraries:
   ```r
   install.packages(c("forecast", "zoo", "ggplot2", "tidyverse"))
   ```
3. Run the analysis by opening **Final Project.Rmd** in RStudio and knitting the report.

## Contributors
- **Gerard Corrales**

