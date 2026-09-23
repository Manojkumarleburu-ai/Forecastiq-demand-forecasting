# Forecastiq-demand-forecasting
AI-driven demand forecasting and production optimization for restaurants and cloud kitchens using machine learning.
# ForecastIQ - AI-Driven Food Demand Forecasting

ForecastIQ is my Master's capstone project in Business Analytics and Data Science at EU Business School.

The project focuses on using AI and machine learning to improve demand forecasting and production planning for quick-service restaurants and cloud kitchens.

## Project Objective

The main objective is to help food-service operators:

- Forecast item-level customer demand
- Reduce overproduction and stock-outs
- Improve food preparation planning
- Reduce food waste
- Support data-driven operational decisions

## Problem Statement

Many restaurants and cloud kitchens still rely on intuition or simple moving averages for demand forecasting.

These methods may not fully capture factors such as:

- Historical sales
- Seasonality
- Weather
- Holidays
- Promotions
- Day-of-week patterns
- Local demand variations

ForecastIQ was designed to combine these signals into a more advanced forecasting approach.

## Data

The proof of concept used anonymized historical sales data from a partner cloud kitchen.

Note: The original dataset is not published in this repository because it contains private business data.

Synthetic or sample datasets can be used for demonstration purposes.

## Machine Learning Models

The project explores multiple forecasting approaches:

- SARIMA
- XGBoost
- LightGBM
- LSTM

These models were selected to capture both time-series patterns and multiple external demand signals.

## Project Results

The proof-of-concept analysis demonstrated:

- Approximately 23% improvement in MAPE compared with a moving-average baseline
- Estimated food-waste reduction of 18-31%, depending on product category

These results represent early-stage proof-of-concept findings and require further validation through commercial pilots.

## Technology Stack

### Programming
- Python
- SQL

### Machine Learning
- Scikit-learn
- XGBoost
- LightGBM
- TensorFlow
- Time Series Forecasting

### Data and Analytics
- Pandas
- NumPy
- Data Visualization
- Statistical Analysis

### Data Engineering and MLOps
- Snowflake
- dbt
- MLflow
- Apache Airflow
- Docker
- Kubernetes

### Cloud
- AWS
- AWS SageMaker

### Application Architecture
- FastAPI
- React.js
- REST APIs

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Baseline Forecasting
6. Machine Learning Model Development
7. Model Evaluation
8. Demand Forecast Generation
9. Production Quantity Recommendation
10. Dashboard and Reporting Design

## Key Evaluation Metric

The main forecasting metric used in the proof of concept was:

**MAPE - Mean Absolute Percentage Error**

MAPE was used to compare model predictions with the existing moving-average forecasting baseline.

## Business Impact

ForecastIQ is designed to support restaurant operators by converting forecasting outputs into practical operational recommendations.

Potential benefits include:

- Lower food waste
- Better inventory planning
- Improved preparation decisions
- Reduced stock-outs
- Better use of historical sales data
- Improved operational efficiency

## Future Development

Future work may include:

- Real-time POS integrations
- Automated model retraining
- Additional external demand signals
- Multi-location forecasting
- Model monitoring
- Interactive dashboards
- Commercial pilot validation

## Author

**Manoj Kumar Leburu**

Business Analytics and Data Science  
EU Business School, Munich

LinkedIn:  
https://www.linkedin.com/in/manoj-kumar-leburu-b11a97222
