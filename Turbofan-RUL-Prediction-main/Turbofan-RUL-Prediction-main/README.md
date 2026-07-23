# Turbofan Engine Remaining Useful Life (RUL) Prediction

## Project Overview

This project focuses on predicting the Remaining Useful Life (RUL) of turbofan aircraft engines using Machine Learning techniques and sensor data. The objective is to estimate the number of operational cycles remaining before engine failure, enabling predictive maintenance and reducing unexpected breakdowns.

## Dataset

Dataset Source:
NASA CMAPSS Turbofan Engine Degradation Simulation Dataset

The dataset contains:

* Engine ID
* Operational Cycles
* Operational Settings
* Multiple Sensor Measurements
* Engine Performance Data

## Objectives

* Analyze engine degradation patterns using sensor data.
* Calculate Remaining Useful Life (RUL) for each engine.
* Perform data preprocessing and feature engineering.
* Train a machine learning model for RUL prediction.
* Evaluate model performance using Mean Absolute Error (MAE).
* Develop a maintenance recommendation system.
* Classify engine health conditions based on predicted RUL.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Methodology

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Remaining Useful Life (RUL) Calculation
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Train-Test Split
7. Model Training using Random Forest Regressor
8. Model Evaluation
9. RUL Prediction Generation
10. Maintenance Recommendation System
11. Visualization and Performance Analysis

## Model Used

* Random Forest Regressor

## Results

### Model Performance

* Mean Absolute Error (MAE): 1.752

The low MAE value indicates that the model successfully learned engine degradation behavior and can accurately estimate the remaining operational life of engines.

### Sample Prediction Results

| Actual RUL | Predicted RUL |
| ---------- | ------------- |
| 79         | 79.91         |
| 2          | 8.88          |
| 34         | 33.00         |
| 17         | 20.74         |
| 74         | 71.01         |

## Additional Features Implemented

### Predictive Maintenance Recommendation System

Based on the predicted RUL, the system automatically classifies engine condition:

* Healthy
* Maintenance Soon
* Critical

This enables proactive maintenance scheduling and reduces the risk of unexpected engine failures.

### Sensor Correlation Heatmap

A sensor correlation heatmap was generated to analyze relationships between operational settings and sensor measurements.

### Actual vs Predicted RUL Visualization

A comparative graph was generated to evaluate prediction accuracy and model performance.

## Project Files

* Turbofan_RUL_Prediction.ipynb
* rul_predictions_enhanced.csv
* rul_graph.png
* sensor_heatmap.png
* README.md

## Applications

* Aircraft Engine Maintenance
* Predictive Maintenance Systems
* Industrial Equipment Monitoring
* Reliability Engineering
* Condition-Based Maintenance

## Future Scope

* Implement XGBoost and Gradient Boosting models.
* Develop a real-time monitoring dashboard using Streamlit.
* Integrate live sensor data for continuous prediction.
* Apply deep learning models such as LSTM for advanced forecasting.
* Deploy the solution as a web-based predictive maintenance platform.

## Conclusion

This project demonstrates the application of machine learning techniques for predictive maintenance and Remaining Useful Life estimation. The developed model provides accurate predictions and maintenance recommendations, helping organizations improve reliability, reduce downtime, and optimize maintenance costs.

## Note

The trained model file (`rul_model.pkl`) is not included in this repository because its size exceeds GitHub's recommended upload limits.

The model can be recreated by running the notebook from start to finish. All preprocessing, feature engineering, model training, and prediction generation steps are included in the notebook.
