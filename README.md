# Heart-disease-prediction-ML
1. [Problem Definition](#problemdefinition)
2. [Data Collection](#dataset)
3. [Data Preprocessing](#datapreprocessing)
4. [EDA](#eda)
5. [Feature Selection](#featureselection)
6. [Model Training](#training)
7. [Testing & Evaluation](#testing)
8. [Hyperparameter Tuning](#hypertuning)




## Problem Definition

**Problem Definition:**
The aim of this project is to develop a machine learning model that can predict the likelihood of an individual having heart disease based on various health-related features. The model will be trained on a dataset containing information such as age, gender, cholesterol levels, blood pressure, and other relevant factors. The primary objective is to create a reliable and accurate predictive tool that can assist in early identification and intervention for individuals at risk of heart disease, ultimately contributing to improved healthcare outcomes.

## Data Collection

[Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

This dataset has 1025 instances and 14 attributes.

Here is the attribute description

1. **age:** Age of the individual (numerical).
2. **sex:** Gender of the individual (categorical: 0 for female, 1 for male).
3. **cp:** Chest pain type (categorical: 0-3, indicating different types of chest pain).
4. **trestbps:** Resting blood pressure (numerical).
5. **chol:** Serum cholesterol level in mg/dL (numerical).
6. **fbs:** Fasting blood sugar > 120 mg/dL (categorical: 0 for false, 1 for true).
7. **restecg:** Resting electrocardiographic results (categorical: 0-2, indicating different results).
8. **thalach:** Maximum heart rate achieved (numerical).
9. **exang:** Exercise-induced angina (categorical: 0 for no, 1 for yes).
10. **oldpeak:** ST depression induced by exercise relative to rest (numerical).
11. **slope:** Slope of the peak exercise ST segment (categorical: 0-2).
12. **ca:** Number of major vessels (0-3) colored by fluoroscopy.
13. **thal:** Thalassemia - a blood disorder (categorical: 0-3, indicating different types).
14. **target:** Presence of heart disease (categorical: 0 for no disease, 1 for presence of disease).

These are the attributes if the respective dataset.
