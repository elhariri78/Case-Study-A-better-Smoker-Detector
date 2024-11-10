# A Better Smoker Detector

## Objective
This project aims to build a predictive model that can determine if an individual is a smoker based on various features available in an insurance dataset. The goal is not only to make accurate predictions but also to ensure the model is optimized for the best performance.

## Dataset Overview
The dataset used in this project contains the following features:

- `age`: Age of the primary beneficiary.
- `sex`: Gender of the insurance contractor (`female`, `male`).
- `bmi`: Body Mass Index (BMI), which provides an understanding of body weight in relation to height (kg/m²).
- `children`: Number of children/dependents covered by health insurance.
- `smoker`: Smoking status (`smoker`, `non-smoker`).
- `region`: Residential area in the US (`northeast`, `southeast`, `southwest`, `northwest`).
- `charges`: Individual medical costs billed by health insurance.

## Problem Statement
Given various features in the dataset, the objective is to predict whether an individual is a smoker or not.

## Project Steps

### 1. Data Preprocessing
- Handle missing values.
- Encode categorical variables (e.g., `sex`, `region`).
- Scale/normalize numerical values (e.g., `age`, `bmi`, `charges`).

### 2. Exploratory Data Analysis (EDA)
- Visualize the distribution of numerical features.
- Analyze correlations between features.
- Investigate the relationship between features like `age`, `bmi`, `charges`, and smoking status.

### 3. Model Building
Try various machine learning models:
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting

### 4. Model Evaluation
Evaluate the models using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score

### 5. Model Improvement
- Tune hyperparameters using GridSearchCV or RandomizedSearchCV.
- Use cross-validation to assess model performance more robustly.

### 6. Conclusion
Summarize the findings and choose the best model based on performance metrics.

## Requirements

To run the project, you need to have Python 3.x installed along with the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the dependencies with:

```bash
pip install -r requirements.txt


git clone https://github.com/elhariri78/smoker-detector.git

cd smoker-detector
