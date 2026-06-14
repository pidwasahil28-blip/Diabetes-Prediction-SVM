# Diabetes-Prediction-SVM
A Data Science &amp; Machine Learning web app that uses a Support Vector Machine (SVM) classifier to predict the likelihood of diabetes in patients based on clinical metrics. Built using Python, Scikit-Learn, Pandas, and NumPy.
# Diabetes Prediction Using Support Vector Machines (SVM)

This project is a Machine Learning pipeline that predicts whether a patient has diabetes based on several diagnostic measurements. It utilizes a Support Vector Classifier (SVC) optimized for medical binary classification tasks. 

---

## 🚀 Features & Workflow
- **Data Preprocessing & Cleaning:** Handles anomalous zero values in medical attributes (like blood pressure or BMI) by replacing them with column-specific medians using Pandas.
- **Feature Scaling:** Uses `StandardScaler` from Scikit-Learn to normalize numerical metrics, preventing larger ranges (e.g., Insulin) from dominating the SVM hyperplane calculation.
- **Robust Machine Learning:** Employs an RBF-kernel Support Vector Machine (SVM) to discover non-linear decision boundaries.

## 📊 Dataset Structure
The predictive model uses the classic Pima Indians Diabetes Dataset containing the following patient metrics:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
- **Outcome** (Target Variable: 0 = Non-Diabetic, 1 = Diabetic)

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn

## 📈 Model Performance
After split-training the dataset (80% Train, 20% Test) and scaling the feature parameters, the model achieved the following performance metrics:

- **Accuracy Score:** [Insert your Accuracy percentage, e.g., 78.57%]
- **Algorithm Used:** Support Vector Classifier (SVC) with RBF Kernel

## 💻 How to Run Locally

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
