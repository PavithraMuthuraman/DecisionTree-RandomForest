# Decision Tree and Random Forest
*Decision Tree and Random Forest for Diabetes Prediction*

**Description:** This project focuses on predicting the likelihood of an individual having diabetes based on their personal characteristics and medical history using Decision Tree and Random Forest algorithms. The dataset includes various features such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age, with the target variable indicating whether the individual has diabetes.

## Project Overview
- **Objective:**  
  Predict the likelihood of an individual having diabetes using Decision Tree and Random Forest classifiers.
- **Models:**
  - **Decision Tree:** A classification algorithm that splits the data into subsets based on feature values to make predictions.
  - **Random Forest:** An ensemble learning method that combines multiple decision trees to enhance prediction accuracy and reduce overfitting.
- **Dataset:**  
  The dataset consists of the following features:
  - **Pregnancies:** Number of pregnancies.
  - **Glucose:** Plasma glucose concentration.
  - **BloodPressure:** Diastolic blood pressure (mm Hg).
  - **SkinThickness:** Triceps skinfold thickness (mm).
  - **Insulin:** 2-Hour serum insulin (mu U/ml).
  - **BMI:** Body Mass Index (weight in kg / (height in m)^2).
  - **DiabetesPedigreeFunction:** A function that scores likelihood of diabetes based on family history.
  - **Age:** Age of the individual.
  - **Outcome:** Target variable indicating whether the individual has diabetes (1 for positive, 0 for negative).

## Files Included
- `diabetes.csv:` The dataset used for training and testing the Decision Tree and Random Forest models.
- `DecisionTree&RandomForest.ipynb:` The Python script that performs data preprocessing, model training, prediction, and evaluation for both Decision Tree and Random Forest classifiers.

## Code Execution
1. **Setup Environment:** Install the required libraries (`numpy`, `pandas`, `scikit-learn`).
2. **Data Loading:** Place `diabetes.csv` in the appropriate directory, then load and inspect the dataset.
3. **Preprocessing:**  
   - Separate the dataset into independent (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age) and dependent variable (Outcome).
   - Split the data into training and testing sets.
4. **Model Training:**
   - Train the Decision Tree classifier on the training data.
   - Train the Random Forest classifier on the same training data.
5. **Prediction:**  
   Predict diabetes outcomes for the test data using both models.
6. **Evaluation:**  
   - Assess the performance of each model using confusion matrix and accuracy score.
   - Compare the performance of the Decision Tree and Random Forest models to determine which provides better predictions.
