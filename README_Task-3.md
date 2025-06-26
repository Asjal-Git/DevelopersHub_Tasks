❤️ Heart Disease Prediction Using Logistic Regression
📝 Task Objective
Heart disease remains a leading cause of death worldwide. This project aims to build a classification model that predicts the presence of heart disease in patients based on various clinical and demographic attributes. The pipeline involves data preprocessing, exploratory data analysis (EDA), model training, evaluation, and feature importance interpretation.

📂 Dataset Used
Source: Kaggle - Heart Disease Dataset

File: heart_disease_uci.csv

Records: 299 cleaned entries after removing missing values

Features: Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Max Heart Rate, etc.

Target:

Original: num (0–4 heart disease stages)

Modified: heart_disease (binary: 0 = No, 1 = Yes)

🤖 Models Applied
Model Used: Logistic Regression (with Scikit-learn)

Preprocessing:

Numerical features: Scaled using StandardScaler

Categorical features: Encoded using OneHotEncoder

Pipeline: Combined preprocessing and model using Pipeline and ColumnTransformer

📊 Key Results and Findings
✅ Model Performance (on Test Set)
Accuracy: 0.8833

Confusion Matrix:

[[31,  4],
 [ 3, 22]]
Precision/Recall/F1-Score:

No Heart Disease (0): F1 = 0.90

Heart Disease (1): F1 = 0.86

AUC-ROC Score: 0.9406 (Excellent classification capability)

🔍 Feature Importance (Top Influencers)
ca: Number of major vessels (positively correlated)

cp_asymptomatic: Chest pain type (positively correlated)

sex_Female: Negative coefficient (lower risk)

oldpeak: ST depression (positively correlated)

thal_reversable defect: Strong risk indicator

🔮 Insights and Next Steps
Logistic Regression provided strong performance and interpretability.

Features like major vessels (ca) and chest pain type were the most impactful.

Future improvements could include:

Exploring models like Decision Trees, Random Forests, or SVMs

Hyperparameter tuning

Cross-validation

Model deployment for real-time inference
