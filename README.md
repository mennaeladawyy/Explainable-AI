# Explainable-AI
## Heart Disease Prediction with XGBoost and Explainable AI
This project uses the UCI Heart Disease Dataset to build a binary classification model using XGBoost, and leverages several Explainable AI (XAI) techniques to interpret the model's predictions.

## 📌 Features
✅ Binary classification: Predicts whether a patient has heart disease or not.

⚙️ XGBoost: High-performance gradient boosting model.

🔍 LIME: Local explanation of individual predictions.

🧠 SHAP: Global and local feature contribution analysis.

📊 Partial Dependence Plots (PDP): Shows the marginal effect of features.

## 📁 Dataset
Source: UCI Machine Learning Repository

## 🚀 How It Works
### Data Preprocessing:

Replace missing values.

Drop incomplete rows.

Normalize features with StandardScaler.

### Binary encode the target: 
0 = No Disease, 1 = Disease.

### Model Training:

Train/test split with stratification.

Train an XGBClassifier on the scaled training set.

### Model Explanation:

LIME: Visualize how features impact individual predictions.

SHAP: Show feature importance globally and locally using bar and force plots.

PDP: Visualize feature effects across prediction space.

## 📷 Example Outputs
LIME Explanation (instance-level)

SHAP Summary Plot (global feature importance)

SHAP Force Plot (individual prediction)

PDP (feature marginal effects)

## 📌 Usage Notes
This project is intended for educational use and demonstrates how to interpret ML models in healthcare.

LIME and SHAP are especially helpful in regulated domains like medicine where interpretability is crucial.

