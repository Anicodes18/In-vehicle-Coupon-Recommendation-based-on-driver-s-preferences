# 🚗 In-Vehicle Coupon Recommendation System

## 📌 Problem Statement
Retailers and service providers often distribute promotional coupons to drivers based on contextual factors such as time, location, passenger status, and weather conditions.
However, not all drivers accept these offers.

This project aims to answer:
Can we predict whether a driver will accept a coupon?
Which contextual and behavioral factors most influence acceptance?
How accurately can machine learning models classify coupon acceptance behavior?

## 📂 Dataset
- Source: UCI Machine Learning Repository
- Size: 12k+ records and 26 features including 1 dependent feature

- Key features: 🚗 Driver attributes (age, occupation, income, etc.)
👥 Passenger information
🌦 Weather conditions
⏰ Time and contextual variables
🎟 Coupon type (restaurant, coffee house, bar, etc.)
✅ Target variable: Coupon accepted (Yes/No)

## 🔍 Approach
- Data cleaning
- Exploratory data analysis
- Feature engineering
- Machine Learning Modeling

## 🤖 Model
- Tested multiple classification algorithms:
  1. Logistic Regression
  2. Ridge and Lasso Regression
  3. Random Forest Classifier

- Evaluation metrics:
  Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC
- Final model performance:
  Random Forest Classifier provided the best accuracy of 76% and an AUC value of 0.83.

## 📊 Key Insights
-  Contextual factors (time of day, passenger type, weather) influenced decision behavior.
- Ensemble Random Forest model outperformed the baseline logistic regression model in predictive accuracy.
- Certain coupon categories had significantly higher acceptance rates.

## 🛠 Tech Used
Python, NumPy, Pandas, Matplotlib, Seaborn, sci-kit learn

## 🚀 Business Impact
This project demonstrates how data-driven recommendation systems can:
🎯 Optimize promotional strategies based on user behavior
📊 Reduce marketing costs through better personalization
📈 Improve targeted marketing effectiveness
💰 Increase coupon redemption rates

A production-ready version of this model could be integrated into in-vehicle infotainment systems or mobile applications to deliver real-time personalized offers.
