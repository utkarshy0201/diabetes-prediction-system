## Disease Prediction System


A machine learning project that predicts the likelihood of diabetes in patients based on diagnostic measurements. Built as an end-to-end ML pipeline in Google Colab.

## Dataset

Pima Indians Diabetes Dataset
- 768 patient records, 8 features, binary outcome (diabetic / non-diabetic)
- Features: Glucose, BMI, Age, Insulin, Blood Pressure, Skin Thickness, Pregnancies, Diabetes Pedigree Function

## Pipeline

- Data Loading: Loaded dataset directly from URL
- EDA: Distribution plots, class balance check, correlation heatmap
- Preprocessing: Replaced invalid zero values with median, StandardScaler, 80/20 split
- Modelling: Trained and compared Logistic Regression, Random Forest, SVM, XGBoost
- Evaluation: Confusion matrix, ROC-AUC curve, SHAP feature importance
- Demo: Interactive Gradio UI for live predictions

## Results

- Logistic Regression: Accuracy ~77%, ROC-AUC ~0.83
- Random Forest: Accuracy ~78%, ROC-AUC ~0.84
- SVM: Accuracy ~77%, ROC-AUC ~0.83
- XGBoost: Accuracy ~80%, ROC-AUC ~0.85 (best model)

## Key Findings

- Glucose level is the strongest predictor of diabetes
- BMI and Age are the next most significant features
- SHAP analysis confirms model decisions are clinically interpretable

## Tech Stack

Python, pandas, numpy, scikit-learn, XGBoost, SHAP, matplotlib, seaborn, Gradio


## Author

Utkarsh Yadav

B.Tech CSE (AI & ML)

GitHub: https://github.com/utkarshy0201

LinkedIn: https://www.linkedin.com/in/utkarsh-yadav-610572326
