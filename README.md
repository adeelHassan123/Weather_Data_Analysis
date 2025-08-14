# 🌦 Weather Data Analysis

A complete end-to-end weather data analysis and prediction pipeline using **Python**, combining **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, and **model building** with **Random Forest** and **LSTM** to predict precipitation and understand weather patterns.

---

## 📌 Features

- **Data Preprocessing & Cleaning**
  - Duplicate and missing value handling
  - Outlier detection (IQR method) with decision rationale
  - Robust scaling and standardization for skewed distributions
  - Season & month name mapping for time-series understanding
  - Label encoding for categorical variables

- **Exploratory Data Analysis**
  - Histograms & boxplots for univariate distribution analysis
  - Bivariate scatterplots (by Year & Season)
  - Correlation matrix heatmaps
  - Seasonal & monthly precipitation trends

- **Feature Engineering**
  - Seasonal categorization based on months
  - Encoded year and season variables
  - Skewness handling for meteorological data

- **Machine Learning**
  - **Random Forest Regressor**
    - MSE: ~0.800  
    - RMSE: ~0.89  
    - R²: ~0.54

- **Deep Learning**
  - **LSTM (Long Short-Term Memory)**
    - Sequential model with 64 hidden units
    - Adam optimizer, MSE loss
    - Performance compared with Random Forest

- **Model Comparison**
  - Visualized MSE, RMSE, and R² for both ML and DL models

---

## 🛠 Tech Stack

- **Programming Language:** Python
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **ML Models:** Scikit-learn (RandomForestRegressor)
- **DL Models:** TensorFlow/Keras (LSTM)
- **Preprocessing:** RobustScaler, StandardScaler, LabelEncoder
---

## 📊 Example Insights

- **Seasonal Trends:** Precipitation peaks in specific seasons depending on location data.
- **Feature Correlation:** Wind speed, humidity, and temperature significantly correlate with precipitation.
- **Model Performance:** Random Forest performed slightly better in R² score, but LSTM captured sequential dependencies.

