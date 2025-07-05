# Maternal Health Risk Analysis using Machine Learning

<img width="423" height="282" alt="Image" src="https://github.com/user-attachments/assets/a9911c86-a7ec-47d7-a869-c1ef650fd734" />


## BUSINESS UNDERSTANDING
Advancements in data analytics and machine learning have opened new frontiers in healthcare, allowing practitioners to harness existing health data to predict potential risks.

By analyzing key physiological parameters, it becomes possible to flag individuals who may be at elevated risk, even before symptoms become critical

## Problem Statement

Despite the availability of basic clinical data, many health systems lack the tools to convert these indicators into actionable insights for timely risk assessment. In most resource-constrained settings, there is a need for lightweight, interpretable models that can assist healthcare providers in classifying maternal risk levels during routine checkups.

Without early identification, high-risk cases may go unnoticed, potentially resulting in adverse health outcomes for both the mother and the child.


## Objectives

1. Perform exploratory data analysis (EDA) to understand distributions, detect outliers, and examine correlations among clinical indicators.

2. Build and compare multiple classification models (e.g., Logistic Regression, Decision Tree, Random Forest) to predict maternal health risk levels.

3.	Evaluate model performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

4.	Identify and rank influential features affecting maternal health outcomes using feature importance or model coefficients.

## Model Implementation
- Logistic Regression
- Decision Trees.
- Random Forest

## Evaluation
The project's success was measured through:

- Accuracy
- Precision
- Recall
- F1 score
- Confusion Matrices

### Findings
Features such as SystolicBP, Body Temperature, Blood sugar and Heartbeat were significant contributors in determining maternal health risk which can be prioritized in routine health assessments.

The use of simple, interpretable models such as Decision Tree, Logistic Regression makes it feasible to deploy such tools in low-resource healthcare settings without needing advanced computing infrastructure.


## Conclusions:
Training for Healthcare Workers:
Train local health practitioners on interpreting model predictions to strengthen human-machine collaboration in maternal care.

Continuous Data Collection:
Encourage more IoT-based data collection from rural and urban clinics to continuously update and retrain the model for greater accuracy and generalizability.

Expand Feature Set:
Future iterations can include additional features such as hemoglobin levels, prenatal history, or socioeconomic data to improve model precision.

Patient Education:
Use the model’s results to counsel at-risk mothers on lifestyle changes and follow-up actions, strengthening preventive care.
