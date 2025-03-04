# Table of Contents

1. [Car Price Prediction](#car-price-prediction)
   - [Dataset Overview](#dataset-overview)
   - [Approach](#approach)
   - [Key Insights](#key-insights)
   - [Model Development](#model-development)
   - [Data Preprocessing](#data-preprocessing)
   - [Regression Algorithm](#regression-algorithm)
   - [Challenges](#challenges)

---

## Car Price Prediction

### Dataset Overview
The dataset, named "cars_data.csv," contains detailed information about various cars, including their make, model, version, price, make year, engine capacity (CC), assembly, mileage, registered city, and transmission.

### Approach
The objective was to develop an accurate machine learning model for predicting car prices based on their features. The dataset underwent data cleaning and feature engineering to optimize the model. Various regression models, including MLP Regression and Random Forest, were applied to address the non-linearity in the dataset.

### Key Insights
The dataset includes columns such as Make, Model, Version, Price, Make_Year, CC, Assembly, Mileage, Registered City, and Transmission.

### Model Development
The following regression algorithms were applied:

- Random Forest Regressor (MSE: 0.05089615861063002)
- MultiLayer Perceptron (MLP) Regressor (MSE: 0.17064087738626135)

Random Forest Regression performed well on this problem.

### Data Preprocessing
Preprocessing steps included handling missing values, encoding categorical variables, and scaling numerical features using the Standard Scalar technique.

### Regression Algorithm
Random Forest Regression

### Challenges
- Some entries lacked respective labels.
- Encoding categorical variables into numerical values posed challenges.


