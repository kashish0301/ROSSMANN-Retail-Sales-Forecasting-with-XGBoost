# Rossmann Retail Sales Analysis & Forecasting with XGBoost

## Project Structure

## Description of Files

- **Data/store.csv**: Contains details about 1115 drug stores, including features such as promotions and competition.
- **Data/train.csv**: Holds daily sales data for different stores from 2013 to 2015, used for training the sales prediction model.
- **Notebooks/rossman-sales-analysis-code.ipynb**: Jupyter Notebook containing the code for sales analysis and predictions.
- **Report/Rossman-Sales-Analysis-Report_11356488.pdf**: The comprehensive report summarizing the analysis, methodologies, and results.
- **README.md**: This file provides an overview and documentation for the project.


## Introduction
This project involves the analysis and prediction of sales for Rossmann stores using historical sales data. The primary goal is to forecast sales for each store up to six weeks in advance, accounting for various influencing factors such as promotions, competition, holidays, and seasonality.

## Dataset Descriptions
The datasets used in this project are:
- **store.csv**: Contains 1115 records of stores with features like promotion, competition, and StoreType.
- **train.csv**: Contains 1,017,209 records of daily sales from 2013 to 2015 for different stores.
- **test.csv**: Contains data for 1115 stores for which sales and customers are to be predicted for six weeks (August 2015 to September 2015).

## Key Steps
1. **Data Preprocessing**: This includes handling missing data, merging datasets, feature extraction, creation, scaling numerical features, and encoding categorical features.
2. **Exploratory Data Analysis (EDA)**: Conduct univariate and multivariate analysis to identify trends and patterns in sales.
3. **Modeling**: Implement machine learning models to forecast sales, focusing on XGBoost due to its superior performance in handling complex data.
4. **Evaluation**: Assess the model using metrics like Root Mean Square Percentage Error (RMSPE).

## Results
The tuned XGBoost model achieved a low RMSPE of 12.11%, indicating enhanced accuracy in sales forecasting.

## Limitations
- Limited customer insights and geographic bias.
- Lack of external economic factors and historical data constraints.

## Recommendations
- Conduct in-depth outlier analysis and explore time-series forecasting methods for improved insights.

## Usage
To run the analysis, ensure you have the required libraries installed. Use the provided Jupyter notebook (`rossman-sales-analysis-code.ipynb`) to execute the code and reproduce the results.

## References
For further details, refer to the accompanying report: [Rossman-Sales-Analysis-Report_11356488.pdf](Report/Rossman-Sales-Analysis-Report_11356488.pdf).
