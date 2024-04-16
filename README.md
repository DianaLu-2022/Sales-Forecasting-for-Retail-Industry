# Sales Forecasting with Statistical and Machine Learning Methods

## Introduction
Sales forecasting is one of the most challenging issues that the retail industry faces due to various influencing factors such as promotional activities, competition, holidays, seasonality, and geographical location. In this project, I employed statistical and machine learning methods to analyze years of historical sales data to predict the daily sales of a chain of drug stores in Germany, comprising more than 1000 stores, from August 1st to September 17th, 2015. The performance of different analytical methods was evaluated using Root Mean Square Percentage Error (RMSPE) to assess the accuracy of the predictions.

## Methodology
### 1. Data Selection and Preparation
I initially selected a date range from the training data that closely matched the dates in the test data and settled on the period from August 1st to September 15th, which comprised 98,400 records.

### 2. Data Merging and Filtering
The training dataset was merged with store information and filtered to exclude closed stores during the period.

### 3. Feature Processing and Adjustment
Unnecessary features were removed, and adjustments were made to the competition-related data.

### 4. Holiday Labeling
The "StateHoliday" column was labeled to distinguish between holidays and non-holidays.

### 5. Data Encoding
Both One-Hot Encoding and Label Encoding techniques were employed to transform categorical features.

## Exploratory Data Analysis (EDA)
Scatter plots and Correlation Matrix heatmap were utilized to understand the relationships between features and target variables.

## Machine Learning Model Performance
Different regression models including Linear Regression, Random Forest, Decision Tree, and Gradient Boosting were evaluated, with Random Forest performing the best under both One-Hot Encoding and Label Encoding.

## Conclusion
The Random Forest regression model achieved the most outstanding performance, especially under One-Hot Encoding. The data preprocessing steps and model training process are detailed in the respective sections of this report.

Additional Information
For detailed analysis, please refer to `report.pdf`.
To understand the analysis process, please check `Retail_Store_Sales_Forecasting.ipynb`.
