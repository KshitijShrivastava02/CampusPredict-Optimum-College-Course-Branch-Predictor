# CampusPredict-Optimum-College-Course-Branch-Predictor



## Overview

The CampusPredict is a robust machine-learning tool designed to predict the optimal college, branch, and course for JEE aspirants. Leveraging advanced models such as CatBoost, Random Forest, Artificial Neural Networks (ANN), and LSTM, the system provides accurate, data-driven recommendations based on rank, category, and other criteria.

This project aims to bridge the gap between JEE aspirants and informed decision-making by utilizing historical admission data from IITs and NITs, allowing students to receive personalized predictions for their academic future.

## Features

Machine Learning Models: Utilizes CatBoost, Random Forest, ANN, and LSTM for accurate predictions.

Data-Driven Insights: Analyzes historical JEE data (opening/closing ranks, quotas, categories).

User Customization: Allows personalized inputs to generate tailored college and course suggestions.

Advanced Visualizations: Graphical analysis of closing rank trends, category distribution, and program availability.

## Dataset Description

The dataset used in CampusPredict is sourced from the official IIT JEE archives (https://cutoffs.iitr.ac.in). It covers multiple years and includes:

Institution Type: IIT/NIT classification.

Program Details: Program name, duration, and degree.

Admission Parameters: Opening and closing ranks.

Categorical Features: Category (GEN, OBC, SC, etc.), Quota (AI, HS, OS).

Temporal Information: Yearly trends from 2016 to 2025.

## Data Preprocessing

Handling Missing Values: Imputation or exclusion of incomplete records.

Encoding Categorical Data: Categorical features are transformed into numerical values.

Feature Scaling: Standardization of rank values for improved model performance.

## Methodology

The project employs a multi-model approach, using different machine-learning techniques to enhance prediction accuracy.

**1. CatBoost Model**

Handles categorical variables without encoding.

Key Parameters: Learning rate, tree depth, iterations.

Strength: Handles missing values natively, reducing preprocessing effort.

**2. Random Forest**

Ensemble learning model combining multiple decision trees.

Key Parameters: Number of trees, max depth, and random state.

Strength: High interpretability and robust feature importance estimation.

**3. Artificial Neural Network (ANN)**

Deep learning model capturing complex, non-linear relationships.

Key Parameters: Input neurons, hidden layers, activation functions.

Strength: Suitable for high-dimensional data and capturing intricate patterns.

**4. Long Short-Term Memory (LSTM)**

Sequential deep learning model for temporal data.

Key Parameters: Number of units, epochs, batch size.

Strength: Captures year-over-year trends and predicts future outcomes.

## Model Performance Comparison

The table below compares the performance of the models based on mean accuracy across key attributes:
![image](https://github.com/user-attachments/assets/87ab0053-c6f5-4ce8-9488-d97eee222f2e)

## LSTM Model Predictions (e.g for IIT Bombay, Electrical Engineering, AI Quota, GEN Category)
![image](https://github.com/user-attachments/assets/e93fbdab-ac1f-4778-a49f-1df52ba6a829)

## LSTM Prediction Graph
![image](https://github.com/user-attachments/assets/60ec2ee0-7255-4265-8630-1244cb686e38)


## Original Data Comparison
![image](https://github.com/user-attachments/assets/e3640e83-8b79-473e-b193-ba0163957239)

## Key Observations

**Model Accuracy:** Random Forest outperforms other models with an 81% mean accuracy.

**Rank Predictions:** LSTM accurately tracks future closing ranks with minimal deviation from actual values.

**Category Trends:** Significant policy changes (e.g., introduction of GEN-EWS) directly impact rank cutoffs.

**Program Diversity:** Established IITs (IIT Bombay, IIT Kharagpur) offer a greater variety of programs compared to newer NITs.

# Contact

Developed by Kshitij Shrivastava For queries or collaboration, reach out via GitHub or LinkedIn.


