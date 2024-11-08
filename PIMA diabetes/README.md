## Overview
This repository contains the work for my Master's Thesis in AI Applied to Health, imparted by CEMP. The project focuses on the PIMA Diabetes Dataset, a well-known dataset used for predicting the onset of diabetes in patients based on diagnostic measures. The goal of the thesis is to explore and apply machine learning techniques to predict diabetes and to compare the performance of different models.

The work involves several stages of data processing, feature engineering, model building, and evaluation, with a particular focus on Random Forest and XGBoost algorithms.

## Objectives
- Optimize diabetes prediction using machine learning techniques.
- Compare different models' performance on the PIMA Indian Diabetes Dataset.
- Evaluate model accuracy, precision, recall, and other relevant metrics.
- Use advanced techniques such as SMOTE (Synthetic Minority Over-sampling Technique) to handle imbalanced datasets.

 ## Dataset
The dataset used for this thesis is the PIMA Indian Diabetes Dataset, which consists of 768 samples and 8 features. The features include:

- Pregnancies: Number of times pregnant.
- Glucose: Plasma glucose concentration.
- Blood Pressure: Diastolic blood pressure.
- Skin Thickness: Triceps skinfold thickness.
- Insulin: 2-Hour serum insulin.
- BMI: Body mass index.
- Diabetes Pedigree Function: A function that scores the likelihood of diabetes based on family history.
- Age: Age of the patient.
- The target variable (Outcome) is binary, where 1 represents the presence of diabetes and 0 represents the absence.

## Methodology
The thesis work involves:

1. Data Preprocessing:
    - Handling missing values.
    - Scaling and normalization of data.
    - Handling class imbalance using SMOTE.
2. Model Development:
    - Random Forest and XGBoost are trained and evaluated on the dataset.
    - Hyperparameter tuning and model optimization are performed.
3. Model Evaluation:
    - Performance metrics such as Accuracy, Precision, Recall, F1-Score, and AUC are calculated.
    - ROC curves and confusion matrices are plotted to visualize model performance.
## Key Features
- Data Cleaning: Techniques for imputing missing values and handling class imbalances.
- Feature Engineering: Selection and transformation of relevant features for improved model performance.
- Model Optimization: Comparison of different machine learning algorithms (Random Forest and XGBoost) to achieve the best possible prediction accuracy.
- Evaluation Metrics: Detailed performance analysis with visualizations, such as ROC curves and confusion matrices.
## Tools and Libraries
This project was implemented using the following Python libraries:

- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Scikit-learn: For building machine learning models and evaluating performance.
- XGBoost: For training and evaluating XGBoost models.
- Matplotlib & Seaborn: For data visualization and plotting.
- Ptitprince: For creating raincloud plots.
