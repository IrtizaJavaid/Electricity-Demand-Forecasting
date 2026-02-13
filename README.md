# Electricity Demand Forecasting
This project focuses on predicting electricity demand using time series data and machine learning (XGBoost). The work was done in Python with Jupyter Notebook (Anaconda environment).
## Steps 
- **Data Preparation**: Loaded dataset, converted timestamp to datetime, cleaned missing values.
- **Feature Engineering**: Added time-based features (hour, month, weekend), lag features, and rolling statistics.
- **Visualization**: Plotted demand trends, boxplots, scatter plots, and correlation heatmap to understand patterns.
- **Model Training**: Used XGBoost regressor with train/test split (past vs future).
- **Evaluation**: Measured accuracy using RMSE and MAE, and compared actual vs predicted demand.
- **Model Saving**: Exported trained model with joblib for future use.

## Results 
- The model captures demand patterns effectively.
- RMSE and MAE values show good prediction accuracy.
- Prediction curve closely follows actual demand.
