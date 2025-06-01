# Heart Disease Prediction Using Machine Learning

This repository presents a comprehensive machine learning pipeline developed to predict the presence of heart disease in patients based on a variety of clinical features. The project includes data preprocessing, model building, performance evaluation, and model serialization, making it a full end-to-end solution for binary classification in the medical domain.

🧠 Project Objective
Cardiovascular diseases are one of the leading causes of death globally. Early diagnosis can significantly improve a patient’s chance of survival. This project aims to build a reliable machine learning model that can predict the presence of heart disease based on input features such as age, cholesterol level, chest pain type, and more.

📂 Contents
HeartDisease.ipynb – Jupyter Notebook containing the complete workflow.

models/ (optional) – Folder to store serialized trained models using joblib.

README.md – Project documentation.

requirements.txt – List of all required Python libraries (available upon request).

📊 Dataset Description
The dataset used in this project contains several health-related features such as:

Age

Sex

Chest pain type (cp)

Resting blood pressure (trestbps)

Cholesterol level (chol)

Fasting blood sugar (fbs)

Resting ECG results (restecg)

Maximum heart rate achieved (thalach)

Exercise-induced angina (exang)

ST depression induced by exercise (oldpeak)

Slope of the peak exercise ST segment (slope)

Number of major vessels colored by fluoroscopy (ca)

Thalassemia (thal)

Target (presence or absence of heart disease)

⚠️ The target variable is binary (1: presence of heart disease, 0: absence).

⚙️ Workflow Summary
1. Data Preprocessing
Handling missing values (if any)

Encoding categorical features using LabelEncoder

Feature scaling using StandardScaler

2. Handling Imbalanced Data
Applied SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance in the target variable.

3. Model Selection & Training
Several machine learning models were implemented and compared:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

AdaBoost Classifier

Voting Classifier (an ensemble of the best-performing models)

4. Model Evaluation
Evaluation metrics used:

Accuracy Score

Classification Report: Precision, Recall, F1-Score

Confusion Matrix

Feature importance plots for interpretability

5. Model Saving
Best-performing models are saved using joblib for future deployment.

📌 Technologies & Libraries Used
Languages: Python 3.x

Libraries:

pandas, numpy – Data manipulation and analysis

matplotlib, seaborn – Data visualization

scikit-learn – ML models, preprocessing, metrics

imblearn – SMOTE for handling imbalance

joblib – Saving/loading trained models

