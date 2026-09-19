
# Student Academic Outcome Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting students' final academic outcomes using machine learning classification algorithms.

The project uses the Open University Learning Analytics Dataset (OULAD), specifically the `studentInfo.csv` file. The target variable is `final_result`, which contains four possible outcomes:

- Pass
- Fail
- Distinction
- Withdrawn

The project demonstrates data preprocessing, multiclass classification, model evaluation, and feature importance analysis using Python and Scikit-learn.

## 🎯 Objectives

- Explore and understand student-related data.
- Preprocess categorical and numerical features.
- Train multiple machine learning classification models.
- Evaluate model performance using Accuracy and Macro F1 Score.
- Compare model performance through visualizations.
- Analyze Random Forest feature importance.

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Dataset

**Dataset:** Open University Learning Analytics Dataset (OULAD)

**File used:** `studentInfo.csv`

The dataset contains student information such as:

- Course module and presentation
- Gender and region
- Highest education
- Age band
- Previous attempts
- Studied credits
- Disability
- Final result

Only `studentInfo.csv` was used for this project.

## 🔍 Project Workflow

1. Data Loading and Exploration
2. Feature and Target Selection
3. Categorical Feature Encoding
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Model Comparison
8. Feature Importance Analysis

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Original Logistic Regression
- Balanced Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## 📊 Results

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| Original Logistic Regression | 44.62% | 0.30 |
| Balanced Logistic Regression | 35.22% | 0.34 |
| Decision Tree | 33.62% | 0.33 |
| Random Forest | 35.42% | 0.34 |

Accuracy and Macro F1 were used to compare overall performance and performance across the different outcome categories.

## 📈 Feature Importance

Random Forest feature importance analysis identified several features that contributed to the model's predictions, including:

- Studied credits
- Highest education
- Number of previous attempts
- Course module
- Age band

Feature importance indicates how the model used features during prediction. It does not establish causal relationships between features and student outcomes.

## ⚠️ Limitations

- The project uses a limited set of student information from `studentInfo.csv`.
- The models do not use all available OULAD datasets.
- Model performance varies across the four outcome categories.
- Feature importance should not be interpreted as proof of causation.
- Further feature engineering and model tuning could be explored.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/vaishnavitelang179-cmd/student-outcome-prediction.git
   ```

2. Install the required libraries:

   ```bash
   pip install pandas matplotlib scikit-learn jupyter
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook student_academic_outcome.ipynb
   ```

4. Make sure `studentInfo.csv` is available at the file path used in the notebook.

5. Run the notebook cells in order.

## 👩‍💻 Author

Vaishnavi
