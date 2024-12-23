---

# Home Credit Default Risk Prediction: Data Science Final Project

This repository contains the complete workflow for predicting customer default risk for Home Credit. The project was developed as part of the **Data Science Final Project** at **Rakamin Academy** and demonstrates a comprehensive application of data science concepts, including data preprocessing, exploratory data analysis, and machine learning.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Workflow Stages](#workflow-stages)
   - [Stage 0: Preparation](#stage-0-preparation)
   - [Stage 1: Exploratory Data Analysis (EDA)](#stage-1-exploratory-data-analysis-eda)
   - [Stage 2: Preprocessing](#stage-2-preprocessing)
   - [Stage 3: Machine Learning](#stage-3-machine-learning)
   - [Stage 4: Final Presentation](#stage-4-final-presentation)
3. [Key Insights and Results](#key-insights-and-results)
4. [Business Recommendations](#business-recommendations)
5. [How to Use](#how-to-use)

---

## Project Overview

The **Data Science Final Project** focuses on predicting the risk of customer default using historical loan application data. By leveraging robust data preprocessing, feature engineering, and advanced machine learning techniques, this project aims to provide actionable insights to improve credit risk management for Home Credit.

---

## Workflow Stages

### Stage 0: Preparation
- **Tasks**: Data collection, initial data inspection, and understanding business requirements.
- **Deliverables**: Raw datasets and project goals.

### Stage 1: Exploratory Data Analysis (EDA)
- **Techniques**:
  - Statistical analysis of key variables.
  - Visualizations to identify patterns and correlations.
- **Objective**: Identify trends and potential predictors for default risk.

### Stage 2: Preprocessing
- **Steps**:
  1. **Data Cleansing**: Handling missing values, removing duplicates, and transforming features.
  2. **Feature Engineering**: Adding new features such as credit ratios and tenure groups.
  3. **Encoding**: Binary and one-hot encoding for categorical variables.
  4. **Handling Class Imbalance**: Using oversampling (SMOTE) and undersampling techniques.
  5. **Normalization**: Standardizing numerical features to improve model performance.

### Stage 3: Machine Learning
- **Models Used**:
  - **AdaBoost**: Combines weak classifiers into a strong classifier adaptively, achieving high accuracy without requiring complex models (Lin, J., 2024).
  - **Decision Tree**: A flexible algorithm for classification and regression, capable of handling numeric and categorical data while generating intuitive tree structures (Madaan, Mehul, et al., 2021).
  - **Random Forest**: An ensemble of decision trees trained on random data subsets, suitable for classification and regression tasks (Madaan, Mehul, et al., 2021).
  - **KNN (K-Nearest Neighbors)**: A lazy learning algorithm that classifies data points based on their neighbors, effective for handling local data patterns (Nagayjothi, V., 2020).
  - **XGBoost**: Known for its high speed and efficiency, XGBoost excels at processing sparse data and controlling overfitting through regularization (Omoghbehme, M.I., 2021).
  - **Stacking**: Combines predictions from multiple base models through meta-modeling to enhance prediction accuracy (Zeng, L., Sun, J., & Zhou, Y., 2023).
  - **Logistic Regression**: A proven method for predicting loan defaults, with a focus on interest rates as a key predictor (Zhao, S., & Zou, J., 2021).

- **Evaluation Metrics**:
  - ROC-AUC, Recall, Precision, F1-Score, and F2-Score.
- **Tuning**: Hyperparameter optimization for improved model performance.

### Stage 4: Final Presentation
- **Deliverables**:
  - Summary of model results and business insights.
  - Recommendations for improving credit policy and reducing default rates.

---

## Key Insights and Results

- The XGBoost model provided the best balance between recall and precision, making it suitable for identifying high-risk customers.
- The optimized model successfully reduced the predicted default rate from **8.04%** to **0.96%**, aligning with Home Credit's business goals.

---

## Business Recommendations

1. **Focus on Customer Segmentation and Retargeting**:
   - Target high-risk sectors like Consumer Electronics and Connectivity with specialized credit offers.
2. **Enhance Default Prediction Accuracy**:
   - Use demographic and behavioral features for better risk profiling.
3. **Flexible Credit Policies**:
   - Offer competitive interest rates for low-risk customers and incentivize loyalty.

---

## How to Use

1. Clone the repository:
   ```
   git clone https://github.com/your-username/home-credit-default-prediction.git
   ```
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Run the preprocessing and modeling scripts:
   ```
   python preprocessing.py
   python modeling.py
   ```
4. Review the final presentation in the `presentation/` folder.

---
