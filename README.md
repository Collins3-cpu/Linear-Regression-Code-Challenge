# Linear-Regression-Code-Challenge
Exploring Crop Yield Prediction in Maji Ndogo Using Simple Linear Regression
This code challenge applies linear regression techniques to analyze factors affecting standardized crop yields. The goal is to understand environmental and management influences on agriculture in Maji Ndogo.

📋 Project Overview

Objective: Build and evaluate a simple linear regression model to predict standardized crop yield (Standard_yield).

Dataset: Agricultural survey data from Maji Ndogo farms, including geographic, weather, soil, and farm management features.

Focus: Relationship between Ave_temps (average temperature) and crop yield, with broader EDA on multiple factors.

📊 Key Insights
## Data Exploration

Geographic Features: Elevation, slope, location.

Weather Features: Rainfall, temperatures.

Soil & Crop Features: Fertility, pH, soil type, chosen crop.

Management Features: Pollution level, plot size.

## Model Analysis

Simple Linear Regression: Focused on Ave_temps as predictor.

Model Evaluation: Residual analysis, R², MAE, RMSE.

Assumptions Check: Linearity, homoscedasticity, normality of residuals.

## Visualizations

Scatter plots of predicted vs actual values.
Residuals analysis to check model fit and bias.

## 🔍 Analysis Highlights

Identified potential nonlinear relationships or lack of strong linear correlation with temperature.

Highlighted the importance of considering multiple factors (pollution, crop type, etc.).

Discussed model limitations and violations of linear regression assumptions.

# 💡 Recommendations

## Model Enhancement:

Incorporate multiple predictors (multiple linear regression).

Explore polynomial regression for potential nonlinear effects.

Consider crop-specific models.

## Data Improvements:
Remove or handle dummy variables (e.g., latitude/longitude).

Feature engineering for better predictors.

## Sustainable Agriculture:
Use insights for targeted interventions (e.g., pollution control in low-yield areas).
Support data-driven farming decisions for local farmers.

## Further Analysis:

Advanced regression techniques (Ridge, Lasso).

Cross-validation and hyperparameter tuning.

Integration with weather forecasting for predictive analytics.

# 🛠️ Technologies Used

Data Handling: pandas, numpy

Modeling: scikit-learn (LinearRegression)

Visualization: matplotlib, seaborn

Environment: Python 3, Jupyter

📚 Data Source

Maji Ndogo farm survey database (Maji_Ndogo_farm_survey_small.db)

Custom data processors for ingestion and cleaning.
