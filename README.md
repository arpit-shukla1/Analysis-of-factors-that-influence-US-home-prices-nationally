# U.S. Home Prices Prediction Project

This project explores the key factors influencing U.S. home prices over the last 20 years. It leverages publicly available data to build a data science model that predicts home prices using economic, demographic, and market variables.

## Objectives

- Collect and analyze publicly available data to identify factors influencing U.S. home prices nationally.
- Build and evaluate predictive models to understand how these factors impacted home prices.
- Provide insights into the key drivers of housing price trends.

## Project Workflow

### 1. Data Collection
- **Home Prices Proxy**: S&P Case-Shiller Home Price Index, sourced from the [Federal Reserve Economic Data (FRED)](https://fred.stlouisfed.org/).
- **Key Factors**: 
  - Unemployment Rate
  - Employment Rate
  - Per Capita GDP
  - Real Median Household Income
  - Construction Prices
  - Consumer Price Index (CPI)
  - Interest Rates
  - Number of New Houses Supplied
  - Working Population
  - Percentage of Population Above 65
  - Housing Subsidies
  - Number of Households

### 2. Data Cleaning and Processing
- Addressed missing values.
- Converted and standardized date formats.
- Handled outliers and normalized variables.

### 3. Exploratory Data Analysis (EDA)
- Analyzed variable distributions and correlations.
- Visualized trends over time for key economic and demographic factors.

### 4. Model Development
Explored and evaluated multiple regression models:
- Linear Regression
- ElasticNet
- Random Forest
- Gradient Boosting
- Support Vector Regression (SVR)
- XGBoost

#### Model Training and Evaluation
- Metrics: Mean Squared Error (MSE) and R-squared.
- Identified the best-performing model based on low MSE and high R-squared values.

#### Feature Importance
- Analyzed the importance of various factors using models like Random Forest, Gradient Boosting, and XGBoost.

### 5. Results and Visualizations
- Visualized:
  - Actual vs. Predicted home prices for each model.
  - Feature importance to illustrate which variables most influenced home prices.
- Key Insights:
  - Determined the most significant factors driving U.S. home prices over the last two decades.
  - Identified the best model for prediction with strong performance metrics ie. XGBoost.

### 6. Conclusions
- The analysis provides valuable insights into historical trends and key drivers of U.S. home prices.
- The project serves as a foundation for further predictive modeling and understanding real estate dynamics.

## Data Sources
- **Home Prices Proxy**: [S&P Case-Shiller Index](https://fred.stlouisfed.org/).
- **Additional Data**: Federal Reserve Economic Data (FRED) and other publicly available sources.

## Future Work
- Extend the analysis to include regional home price variations.
- Incorporate additional variables like mortgage rates or policy changes.
- Build more advanced predictive models for real-time applications.


