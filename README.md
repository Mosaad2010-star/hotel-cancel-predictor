# Hotel Booking Cancellation Predictor 🏨❌✅

This project aims to predict hotel reservation cancellations and analyze trends in booking behavior using machine learning and regression techniques. It achieves high accuracy in classification, and offers actionable insights for the hospitality industry.

## 1. Data Cleaning & Feature Engineering

- Missing values visualized with `missingno` and appropriately filled.
- Label encoding applied to categorical columns (`agent`, `company`).
- Engineered features include:
  - `total_stay`: Total nights stayed
  - `total_guests`: Sum of adults, children, and babies
  - `weekend_ratio`: Ratio of weekend nights
  - `is_family`: Binary indicator for family bookings
  - `booking_change_rate`: Changes divided by lead time
  - `adr_per_person`: Daily rate per guest
- Outliers visualized with boxplots.
- Correlation heatmaps, pairplots, and treemaps for in-depth understanding.

## 2. Machine Learning - Classification

**Goal:** Predict whether a reservation will be canceled (`is_canceled`).

- Models Used:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Support Vector Machine
  - K-Nearest Neighbors
  - Naive Bayes
  - Extra Trees
  - Gradient Boosting
  - AdaBoost
- Evaluation Metrics:
  - Accuracy
  - ROC-AUC Score
- Comparative ROC Curve plotted to visualize performance.

## 3. Regression Analysis

**Goal:** Predict the Average Daily Rate (`adr`).

- Outliers (`adr > 500`) were removed.
- Linear Regression model trained.
- Evaluation:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
- Scatter plot visualizes actual vs predicted ADR values.

## 4. Temporal & Trend Analysis

- Monthly bookings analyzed by year.
- Violin plots show stay duration by hotel type.
- Pie chart visualizes cancellation distribution.


