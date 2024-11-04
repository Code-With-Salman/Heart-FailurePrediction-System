# Heart-FailurePrediction-System
Listen to Your Heart: Detecting Heart Failure Using Machine Learning is a project aimed at predicting heart disease using a dataset with 11 patient health features. This notebook includes data analysis, preprocessing, and training models with decision trees and random forests, as well as evaluating their effectiveness in forecasting heart failure.
# Heart Failure Prediction System

**Listen to Your Heart: A Failure Detection** is a machine learning initiative aimed at forecasting heart disease using a dataset that consists of 11 health-related features. This notebook addresses data exploration, preprocessing, training models with decision trees and random forests, and evaluating the models' accuracy in predicting heart failure.

# Listen to Your Heart: A Failure Detection

## Introduction

Cardiovascular diseases (CVDs) rank as the leading cause of mortality worldwide, accounting for approximately 17.9 million deaths annually. This project centers on predicting heart disease by leveraging a dataset that encompasses 11 pertinent features.

## Objectives

- Analyze the dataset through visualizations.
- Preprocess and scrutinize the data.
- Develop and assess machine learning models for heart disease prediction.

## Dataset Description

The dataset comprises the following features:

- **Age:** Patient's age (in years)
- **Sex:** Gender (0 = male, 1 = female)
- **Chest Pain Type:** Categorical variable (0 to 3)
- **Resting Blood Pressure:** Measured in mm Hg
- **Serum Cholesterol:** Measured in mg/dl
- **Fasting Blood Sugar:** (0 or 1)
- **Resting Electrocardiographic Results:** (0 to 2)
- **Maximum Heart Rate Achieved:** 
- **Exercise Angina:** (0 or 1)
- **ST Depression Induced by Exercise:** 
- **Slope of the Peak Exercise ST Segment:** (0 to 2)
- **Diabetes:** (0 or 1)
- **Smoking Status:** (0 or 1)
- **Creatinine Levels:** (0 to 2500)
- **Number of Major Vessels Highlighted by Fluoroscopy:** (0 to 3)
- **Thalassemia Status:** 
- **Heart Failure Indicator:** (0 = No, 1 = Yes)

## Implementation

### Libraries Used

- `numpy`, `pandas` for data manipulation
- `seaborn`, `matplotlib` for data visualization
- `scikit-learn` for training and evaluating machine learning models

### Steps Included

1. **Data Exploration**
   - Visualizing relationships between features and the target variable.

2. **Data Preprocessing**
   - Addressing missing and duplicate values, and encoding categorical variables.

3. **Feature Selection**
   - Identifying significant features through statistical testing.

4. **Model Training**
   - Implementing Decision Tree and Random Forest classifiers.
   - Evaluating model performance using metrics such as accuracy, ROC-AUC score, and confusion matrix.

## How to Run the Notebook

1. Ensure all necessary libraries are installed.
2. Load the dataset into a Pandas DataFrame.
3. Follow the outlined steps in the notebook for data exploration, preprocessing, model training, and evaluation.

## Conclusion

This project showcases the use of machine learning techniques to predict heart disease, highlighting the crucial role of early detection and effective management.

## Author

Salman Khizar
