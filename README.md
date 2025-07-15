# Project title
Roadway Congestion Forecasting Software Projest.
About the Project This repository contains the implementation of a Roadway Prdiction Spftware. The project was developed as a mini-project for the 5th semester.
This project focuses on predicting and forecasting traffic volume at multiple junctions using historical traffic data. 
The primary goal is to utilize time-series analysis and deep learning models (GRU) to accurately forecast traffic patterns, enabling better traffic management and urban planning.

# Objective
   *Analyze historical traffic data and identify trends.
   *Perform Exploratory Data Analysis (EDA) for pattern recognition.               
	 *Apply data preprocessing techniques such as normalization, differencing, and stationarity checks.
   *Build a Gated Recurrent Unit (GRU)-based deep learning model for time-series forecasting.
   *Evaluate the model using RMSE (Root Mean Squared Error).
   *Visualize predictions vs actual traffic counts.
	 
# DataSet
  Source: Kaggle traffic prediction dataset
  Features:
    DateTime → Timestamp of observation
    Vehicles → Number of vehicles counted
    Junction → Location identifier (4 junctions)
    Size: Multiple years of hourly traffic data
  Preprocessing Steps:
    Removed unnecessary columns (ID)
  Extracted new features: Year, Month, Day, Hour
  Checked and ensured stationarity using Augmented Dickey-Fuller (ADF) test
  Normalized and differenced the time series for better model performance.

# Tools & Technologies
  Programming Language: Python
	Libraries Used:
            Data Handling: pandas, numpy
            Visualization: matplotlib, seaborn
						Time Series Analysis: statsmodels
            Machine Learning: scikit-learn
           Deep Learning: TensorFlow, Keras
	Model: GRU (Gated Recurrent Unit) Neural Network
 
# Key Learnings
Importance of stationarity and data normalization in time series forecasting.
GRU models perform well in handling sequential data with temporal dependencies
Visualization helps in better feature selection and understanding seasonality

# Future Scope
Implement Bi-directional GRU or LSTM for improved accuracy.
Integrate external factors like weather data, events, or holidays for better predictions.
Deploy the model as a real-time traffic prediction API or dashboard.



