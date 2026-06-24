# Smart City Traffic Forecasting

## Project Overview

This project focuses on predicting traffic volume in a smart city using Machine Learning techniques and historical traffic data. The objective is to analyze traffic patterns across different city junctions and forecast future traffic conditions to support better traffic management and urban planning.

## Dataset

Dataset Source:
https://www.kaggle.com/utathya/smart-city-traffic-patterns

The dataset contains:

* Date and time information
* Junction identifiers
* Vehicle count data
* Historical traffic records

## Objectives

* Analyze historical traffic patterns.
* Perform data preprocessing and feature engineering.
* Build a machine learning model for traffic forecasting.
* Evaluate model performance using error metrics.
* Generate future traffic predictions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab

## Methodology

1. Data Collection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Model Training using Random Forest Regressor
6. Performance Evaluation using Mean Absolute Error (MAE)
7. Traffic Prediction Generation

## Results

Model: Random Forest Regressor

Mean Absolute Error (MAE): 2.864

The model successfully learned traffic patterns and produced accurate traffic forecasts for different city junctions.

## Project Files

* Traffic_Forecasting.ipynb
* traffic_predictions.csv
* README.md

## Future Scope

* Implement advanced forecasting models such as XGBoost and LSTM.
* Develop a web dashboard for real-time traffic prediction.
* Integrate live traffic data for dynamic forecasting.

## Conclusion

This project demonstrates the application of machine learning techniques for smart city traffic forecasting. The developed model can assist city authorities in traffic planning, congestion management, and infrastructure development.

## Note

The trained model file (`traffic_model.pkl`) is not included in this repository because its size exceeds GitHub's recommended file upload limits.

The model can be recreated by running the `Traffic_Forecasting.ipynb` notebook from start to finish. All preprocessing, feature engineering, model training, and prediction steps are included in the notebook.

Repository Contents:

* Traffic_Forecasting.ipynb
* traffic_predictions.csv
* README.md

Model Used:

* Random Forest Regressor

Performance:

* Mean Absolute Error (MAE): 2.864


