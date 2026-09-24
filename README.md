## Heart Disease Prediction

### Overview

This project uses machine learning to predict the presence of heart disease based on patient-related features. The project includes data exploration, preprocessing, visualization, model training, evaluation, and prediction.

### Dataset

The dataset contains **918 records and 12 columns**.

The features include:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Angina
- Oldpeak
- ST Slope
- Heart Disease

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Joblib
- Jupyter Notebook

### Project Workflow

1. Load the dataset
2. Explore the dataset
3. Check data types and missing values
4. Perform exploratory data analysis
5. Visualize the data
6. Encode categorical features
7. Separate features and target variable
8. Split the data into training and testing sets
9. Apply feature scaling using StandardScaler
10. Handle class imbalance using SMOTE
11. Train multiple machine learning models
12. Evaluate the models
13. Save the trained SVM model and scaler
14. Make predictions using the saved model

### Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost Classifier

### Model Accuracy

| Model | Accuracy |
|---|---:|
| Logistic Regression | 85.87% |
| Decision Tree | 75.00% |
| Random Forest | 87.00% |
| Support Vector Machine (SVM) | 88.04% |
| XGBoost | 86.96% |

### Model Saving

The trained SVM model and StandardScaler were saved using Joblib:

- `svc_model_HeartDisease.pkl`
- `scaler_HeartDisease.pkl`

### Prediction

The saved SVM model is used to make predictions based on user-provided patient information.

### Project Structure

```text
Heart-Disease-Prediction/
├── HeartDisease.ipynb
└── README.md
