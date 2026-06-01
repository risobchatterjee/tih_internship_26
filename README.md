# Student Academic Performance Prediction

This repository contains the Summer Internship 2026 project work for the IDEAS TIH Programme.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/risobchatterjee/tih_internship_26/blob/main/11-Student_Academic_Performance_Prediction_Spring_2026.ipynb)

## Project Overview
This project builds a machine learning workflow using a Decision Tree Classifier to predict student academic performance categories based on various numerical and categorical features.

## Workflow Implemented
1. **Data Loading & Exploration:** Initialized pandas DataFrame and checked data dimensions.
2. **Data Preprocessing:** Handled missing values using median (numerical) and mode (categorical) strategies, followed by Label Encoding.
3. **Feature Engineering:** Separated target features and applied standard `MinMaxScaler` feature scaling.
4. **Model Training:** Configured and evaluated a `DecisionTreeClassifier` baseline.
5. **Insights:** Extracted model feature importances to determine key driving metrics.
