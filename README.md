# Telecom Churn Prediction

## Overview

This project aims to predict customer churn in the telecom industry using the XGBoost algorithm. Churn prediction is crucial for telecom companies to identify customers who are likely to leave and take proactive measures to retain them. By analyzing customer data, we can gain insights into factors contributing to churn and help improve customer retention strategies.

The dataset contains 7,043 samples with 20 features, including various customer attributes and a target variable indicating churn status. The project includes preprocessing, exploratory data analysis (EDA), and the implementation of an XGBoost model for churn prediction.

### Churn Distribution

<div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/hiephoangt/Telecom-Churn-Prediction/main/Image/Churn%20Distribution.jpg" alt="Churn Distribution" width="400"/>
</div>

### Data Analysis

1. **Exploratory Data Analysis**
   - Descriptive analysis of the data, including basic statistical metrics like mean, median, and distribution.
   - Examining the relationship between variables and churn rates.


2. **Data Preprocessing**
   - Handling missing values.
   - Handling outliers.
   - Encoding categorical variables for model input.

3. **Model Training**
   - Utilizing a XGBoost model to train the data.
   - Evaluating the model using metrics such as accuracy, F1_score, Recall score, Precision Score and Cross Val Score.


## Results
![Model Performance](https://raw.githubusercontent.com/hiephoangt/Telecom-Churn-Prediction/main/Image/Model%20Performance.jpg)

**Here is visualization of the features that significantly influence churn:**

<div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/hiephoangt/Telecom-Churn-Prediction/main/Image/Top%20Feature%20Importance.jpg" alt="Top Feature Importance" width="400"/>
</div>


---

## How to View
To view the Jupyter Notebook containing the analysis, you can access the raw file using the link below:

[Telecom Churn Prediction Notebook](https://github.com/hiephoangt/Telecom-Churn-Prediction/blob/main/Telecom_Churn_Prediction.ipynb)
