# Telecom Customer Churn Prediction

This repository contains code for performing a thorough analysis of telecom customer churn prediction using various machine learning models, focusing particularly on Logistic Regression, Random Forest, and XGBoost. The code is accompanied by a summary of the analysis, with a detailed interpretation of the XGBoost model's output.

## Overview

The code performs the following steps:

1. **Data Loading and Exploration:**
   - The dataset is loaded from Kaggle, and basic exploratory data analysis is performed to understand its structure and characteristics.

2. **Data Preprocessing:**
   - Data preprocessing steps are conducted, including handling missing values, mapping categorical variables to numerical values, and creating dummy variables for categorical features.

3. **Feature Engineering:**
   - Duplicate features and rows are removed, and feature importance is analyzed using both Random Forest and XGBoost models.

4. **Model Training and Evaluation:**
   - The dataset is split into training and testing sets.
   - Logistic Regression, Random Forest, and XGBoost classifiers are trained and evaluated using various evaluation metrics such as accuracy, confusion matrix, and classification report.

5. **Hyperparameter Tuning:**
   - GridSearchCV is employed to optimize the hyperparameters of the Random Forest and XGBoost models, improving their performance.

6. **Interpreting XGBoost Model Output:**
   - The XGBoost model's feature importance is analyzed, and a bar chart is generated to visualize the most influential features.
   - Key features such as "InternetService_Fiber_Optics" and "2-year contract" are identified as significant contributors to the model's predictions, while less impactful features like "Tenure_4" and "Partner" are also highlighted.

## Interpretation of Results

The output result offers valuable insights into which features play crucial roles in predicting customer churn for the XGBoost model. It identifies the most influential features and helps prioritize them for further analysis or business decision-making processes. Additionally, it highlights less important features, which may guide feature selection or refinement efforts in future iterations of the predictive model.

## Dataset
The dataset used in this analysis can be found on Kaggle: [Telecom Company Call-Center Dataset](https://www.kaggle.com/datasets/datazng/telecom-company-churn-rate-call-center-data?select=Telecom+Company+Call-Center-Dataset.xlsx).

## Dependencies
The code is written in Python and requires the following libraries:
- numpy
- pandas
- scikit-learn
- xgboost
- matplotlib
- seaborn

## Usage
1. Clone the repository:

   ```
   git clone https://github.com/yourusername/telecom-churn-prediction.git
   ```

2. Install the dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook or Python script to execute the analysis.

## Contributors
- [Your Name](https://github.com/ssingh2306)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
