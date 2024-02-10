# Sales Forecast
Overview
This project aims to predict future sales based on historical data, employing various machine learning techniques. The dataset, sourced from 'train.csv', contains detailed information about sales across different stores, items, and dates. The project follows a systematic process, including data exploration, preprocessing, feature engineering, model training, and performance evaluation.

# Key Steps
Data Exploration and Preprocessing
The initial step involves loading the sales data and exploring its structure.
Unnecessary columns ('store' and 'item') are removed, and the 'date' column is converted to a datetime format.
Monthly aggregates of sales are computed for a comprehensive overview of the data.
Data Visualization
The monthly customer sales are visualized using matplotlib, providing insights into the sales trends over time.
Time Series Analysis
To make the sales data stationary, the difference on the sales column is computed.
Feature Engineering
A supervised learning dataset is created by shifting the sales difference for the past 12 months.
Data Splitting and Scaling
The dataset is split into training and testing sets, and MinMaxScaler is applied for scaling.
Linear Regression Modeling
A Linear Regression model is implemented to predict future sales.
Model performance is evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
Visualization of Predictions
The linear regression predictions are visualized against the actual sales, offering a clear comparison.
Model Performance
Linear Regression
Mean Squared Error (MSE): 16221.27
Mean Absolute Error (MAE): 12433.18
R-squared (R2): The value varies based on the predicted and actual sales values.
# Dependencies
pandas
numpy
matplotlib
xgboost
scikit-learn
tensorflow
# How to Use
Ensure the required dependencies are installed.
Run the provided Python script for sales forecasting using Linear Regression.
Explore the visualizations and model performance metrics.
# Note
This project lays the foundation for sales forecasting, and further experimentation can be conducted with different machine learning algorithms or parameter tuning to align with specific business requirements.
