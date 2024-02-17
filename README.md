
# NYC Airbnb Price Prediction 

A machine learning project aims to predict the Airbnb listing price in NYC based on listing information (e.g., room type, number of reviews, neighborhood group). The goal is to help property owners in New York City optimize their listings to maximize rental income while maintaining competitive pricing.




## File Description

The project consists of the following files:

1. AB_NYC_2019.csv: The dataset of Airbnb listings and metrics in NYC, NY, USA (2019), obtained from Kaggle (https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data).
2. ML_Project_Airbnb_Prices.ipynb: The code file including data preparation, exploratory analysis, data preprocessing, hyperparameter tuning, and model selection.
3. ML_Project_Airbnb_Prices.pdf: The report file including communication of the related business question and statistical question, explanation of the exploratory analysis and machine learning workflow, and the interpretation of model results.


## How to Reproduce Results

To reproduce the analysis and results of this project, follow these steps:

1. Ensure that you have Python 3.x installed along with the following packages: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn.
2. Download the ML_Project_Airbnb_Prices.ipynb and the AB_NYC_2019.csv to a local directory.
3. Open the Jupyter notebook and run all cells in the notebook sequentially to perform the data preparation, exploratory analysis, data preprocessing, hyperparameter tuning, and model selection.


## Model Selection and Optimization 

The models used include Dummy Regressor, Decision Tree Regressor, Ridge Regression, Lasso Regression, and XGBoost Regression.
Hyperparameter tuning was performed using RandomSearchCV, with the R^2 score as the performance metric.
For detailed explanations of each step and the rationale behind model choices, refer to the project report.