# Credit Card Transactions Analysis

**Project Overview:**  
The project involved the analysis of credit card transactions in India, focusing on exploring spending patterns across different cities using exploratory data analysis (EDA) and time series forecasting models.

**Dataset:**  
The dataset "Credit card transactions - India - Simple.csv" includes the following columns:
- **City:** The city where the transaction occurred.
- **Date:** The transaction date.
- **Card Type:** The type of credit card used.
- **Exp Type:** The expense category associated with the transaction.
- **Gender:** The cardholder's gender.
- **Amount:** The transaction amount.

**Analysis:**  
The analysis comprised the following steps:
1. **Exploratory Data Analysis (EDA):**
   - Examined data distribution, trends, and anomalies.
   - Explored correlations between variables.
2. **Data Understanding:**
   - Summarized key statistics and insights from the dataset.
3. **Model Training:**
   - Employed three different time series forecasting models: 
     - **ARIMA (AutoRegressive Integrated Moving Average)**
     - **SARIMA (Seasonal AutoRegressive Integrated Moving Average)**
     - **Holt-Winters**


**Files:**
- `Credit card transactions - India - Simple.csv`: The primary dataset.
- `IO_DATASCIENCE.ipynb`: Code.
- `README.md`: An overview of the project.

**Model Performance Evaluation Metrics:**  
The following two metrics were used in the evaluation of the models:
- **MAE (Mean Absolute Error):** This metric calculates the average differences between predicted and actual values, quantifying prediction errors.
- **MAPE (Mean Absolute Percentage Error):** This metric calculates the error in terms of percentage, providing additional insight into model performance.
