# 🩺 Diabetes Prediction System

## 🚀 Overview

This project is a complete **Machine Learning classification pipeline** that predicts whether a person is likely to have diabetes based on medical attributes.

It demonstrates **data preprocessing, outlier handling, scaling, model comparison, and evaluation**, making it a strong end-to-end healthcare ML project.

---

## ✨ Features

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning (handling zero values as missing)
* 📉 Outlier Removal (Z-score method)
* ⚙️ Feature Scaling (StandardScaler)
* 🤖 Multiple ML Models Comparison
* 📈 Model Evaluation (Accuracy, Confusion Matrix, Classification Report)

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* SciPy

---

## 📂 Dataset

* Dataset: `diabetes.csv`
* Features include:

  * Glucose
  * Blood Pressure
  * BMI
  * Insulin
  * Skin Thickness
  * Age
  * Outcome (Target)

---

## ⚙️ Project Workflow

### 1. Data Understanding

* Dataset overview (shape, info, stats)
* Visualization using histograms

---

### 2. Data Cleaning

* Replaced invalid zero values with median:

  * Glucose
  * BloodPressure
  * SkinThickness
  * Insulin
  * BMI

---

### 3. Outlier Removal

* Used **Z-score method**
* Removed extreme values for better model performance

---

### 4. Exploratory Data Analysis

* Histograms for feature distributions
* Correlation heatmap

---

### 5. Feature Scaling

* Applied **StandardScaler** to normalize data

---

### 6. Model Training

Tested multiple ML models:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVC)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Linear Regression (baseline)

---

### 7. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## ▶️ How to Run

### 1. Install dependencies

```bash id="j3b7k2"
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### 2. Run the script

```bash id="n8w2q1"
python diabetes_prediction.py
```

---

## 📊 Results

* Compared multiple models
* **SVC used as final model**
* Achieved strong classification performance

---

## 📈 Key Insights

* 🧪 Glucose level is a major predictor
* ⚖️ BMI significantly impacts diabetes risk
* 💉 Insulin & Skin Thickness show moderate influence
* 📊 Proper preprocessing improves model accuracy significantly

---

## 🚀 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Build a Streamlit web app
* Deploy as REST API
* Add real-time prediction UI
* Use advanced models (XGBoost, LightGBM)

---

## 👨‍💻 Author

Built as a complete ML classification project showcasing:

* Data preprocessing
* Model comparison
* Healthcare analytics

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!
