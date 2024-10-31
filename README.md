# AI-Powered Forecasting for Agricultural Productivity

This project aims to forecast agricultural productivity using a Keras-based machine learning model. By analyzing environmental, climatic, and soil-related features, this model helps predict crop yields, aiding farmers and agricultural planners in making informed decisions to improve productivity and resource management.

## Dataset
The dataset includes variables like soil type, climate data, and historical yield records. Data preprocessing involved handling missing values, normalizing features, and encoding categorical variables to prepare for training.
**Source**:https://github.com/Shyamkumarnagilla/AI-Powered-Forecasting-for-Agricultural-Productivity/blob/main/Crop_recommendation.csv

## Modeling
- **Algorithm Used**: Keras Sequential model with multiple dense layers | GridSearchCV |
- **Training Score**: 0.9688
- **Test Score**: 0.9561

## Evaluation
The model demonstrated high accuracy and reliable performance across various classes of productivity levels. Below are key metrics:
- **Accuracy**: 0.96
- **Precision, Recall, F1-Score (Macro Average)**: 0.96
- **Support**: 660 samples

- ## Visualizations
Feature importance and prediction visualizations were created to offer insights into which variables most significantly impact agricultural productivity.

## Conclusion
The model achieves a high accuracy of 0.96, demonstrating strong potential in predicting agricultural productivity. This tool can support timely decision-making in agricultural management, from crop selection to resource allocation.
