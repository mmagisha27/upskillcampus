# Smart City Traffic Forecasting and Traffic Monitoring Dashboard

## Project Overview

This project focuses on predicting traffic volume in a smart city using Machine Learning techniques and historical traffic data. The objective is to analyze traffic patterns across different city junctions and forecast future traffic conditions to support better traffic management and urban planning.

In addition to traffic forecasting, an interactive dashboard and visualization system have been developed to provide a more practical and user-friendly traffic monitoring solution.

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
* Develop an interactive dashboard for traffic prediction.
* Visualize traffic density patterns using heatmaps.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Streamlit
* Google Colab

## Methodology

1. Data Collection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Traffic Pattern Visualization
6. Model Training using Random Forest Regressor
7. Performance Evaluation using Mean Absolute Error (MAE)
8. Traffic Prediction Generation
9. Dashboard Development using Streamlit

## Additional Features Implemented

### Traffic Density Heatmap

A heatmap was developed to visualize average traffic volume across different junctions and hours of the day. This helps identify peak traffic periods and high-density traffic zones.

### Interactive Traffic Forecasting Dashboard

A Streamlit-based dashboard was developed to allow users to:

* Select Year
* Select Month
* Select Day
* Select Hour
* Select Junction

The dashboard generates real-time traffic predictions based on user inputs.

### Optimized Model Deployment

A lightweight optimized machine learning model (`traffic_model_small.pkl`) was created for efficient deployment and faster prediction generation.

## Results

Model: Random Forest Regressor

Mean Absolute Error (MAE): 2.864

The model successfully learned traffic patterns and produced accurate traffic forecasts for different city junctions.

## Project Files

* Traffic_Forecasting.ipynb
* traffic_predictions.csv
* traffic_model_small.pkl
* heatmap.png
* dashboard.png
* README.md

## Dashboard Preview

The project includes an interactive traffic forecasting dashboard developed using Streamlit. Users can provide traffic-related inputs and receive predicted traffic volume instantly.

## Future Scope

* Implement advanced forecasting models such as XGBoost and LSTM.
* Integrate real-time traffic feeds from IoT devices and sensors.
* Develop traffic congestion alert systems.
* Enable route optimization and smart signal control.
* Deploy the dashboard on cloud platforms for public access.

## Conclusion

This project demonstrates the application of machine learning techniques for smart city traffic forecasting. The developed forecasting model, visualization system, and interactive dashboard can assist city authorities in traffic planning, congestion management, and infrastructure development.

## Note

The original trained model file exceeded GitHub's recommended upload size limits. Therefore, an optimized lightweight model (`traffic_model_small.pkl`) has been included for deployment and demonstration purposes.

All preprocessing, feature engineering, model training, visualization, and prediction generation steps are available in the notebook.

Repository Contents:

* Traffic_Forecasting.ipynb
* traffic_predictions.csv
* traffic_model_small.pkl
* heatmap.png
* dashboard.png
* README.md

Model Used:

* Random Forest Regressor

Performance:

* Mean Absolute Error (MAE): 2.864
