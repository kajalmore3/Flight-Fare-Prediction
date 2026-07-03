# Flight Price Prediction using Machine Learning

## Project Overview

Flight ticket prices are highly dynamic and influenced by several factors such as airline, source, destination, journey date, duration, and number of stops. This project aims to analyze historical flight fare data and build machine learning models capable of accurately predicting future flight ticket prices.

The developed model can help customers make informed travel decisions and assist airlines in understanding pricing trends.

---

## Problem Statement

Flight ticket prices change frequently and are difficult to predict. The objective of this project is to analyze historical flight fare data and build a machine learning model that can predict future flight prices based on various flight-related features.

---

## Project Objectives

- Perform Exploratory Data Analysis (EDA).
- Identify important factors affecting flight prices.
- Handle missing values and outliers.
- Perform feature engineering and data preprocessing.
- Build multiple machine learning models.
- Compare model performance.
- Apply hyperparameter tuning.
- Select the best model for production deployment.

---

## Dataset Information

The dataset contains information related to:

- Airline
- Date of Journey
- Source
- Destination
- Route
- Departure Time
- Arrival Time
- Duration
- Total Stops
- Additional Information
- Price (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Data Preprocessing

The following preprocessing steps were performed:

- Missing Value Treatment
- Outlier Detection and Removal
- Date Feature Extraction
- Time Feature Extraction
- Duration Conversion
- Categorical Variable Encoding
- Feature Engineering

---

## Exploratory Data Analysis (EDA)

Key insights obtained from EDA:

- Jet Airways flights tend to have higher fares.
- Flight prices increase with the number of stops.
- Longer flight durations generally result in higher ticket prices.
- Source and destination significantly impact fare prices.
- Seasonal and journey date factors influence ticket costs.

---

## Machine Learning Models Used

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Tuned Random Forest Regressor

---

## Hyperparameter Tuning

GridSearchCV was used to optimize the Random Forest model parameters:

- n_estimators
- max_depth
- min_samples_split

This improved prediction accuracy and reduced error.

---

## Model Evaluation Metrics

The following metrics were used to evaluate model performance:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Model Comparison

| Model | Performance |
|---------|-------------|
| Linear Regression | Baseline Model |
| Decision Tree | Improved Performance |
| Random Forest | High Accuracy |
| Tuned Random Forest | Best Performance |

---

## Best Model

**Tuned Random Forest Regressor** was selected as the final model because it achieved:

- Highest R² Score
- Lowest Prediction Error
- Better Generalization Performance

---

## Challenges Faced

- Handling missing values.
- Converting duration from text format to numerical values.
- Encoding categorical variables.
- Detecting and removing outliers.
- Hyperparameter tuning for model optimization.

---

## Future Scope

- Integrate real-time flight booking data.
- Include weather and holiday information.
- Implement advanced models such as XGBoost.
- Deploy the model using Streamlit or Flask.
- Create a web application for fare prediction.

---

## Conclusion

This project successfully analyzed flight fare data and developed machine learning models for fare prediction. After comparing multiple models, the Tuned Random Forest Regressor achieved the best performance and was selected as the final model. The solution can help customers estimate future flight prices and support better travel planning.

---

## Author

Kajal More

Data Analyst | Machine Learning 
