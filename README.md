# CodeAlpha_Disease-Prediction-from-Medical-Data

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Overview

This project is a complete Machine Learning Healthcare Prediction System that predicts multiple diseases using medical datasets and classification algorithms.

The project demonstrates:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning model training
- Model evaluation
- Prediction system creation

It is designed as an internship/final year AI-ML project and runs perfectly on Google Colab.

---

# 🚀 Features

✅ Heart Disease Prediction  
✅ Diabetes Prediction  
✅ Breast Cancer Prediction  
✅ Exploratory Data Analysis  
✅ Data Visualization  
✅ Multiple ML Algorithms  
✅ Model Comparison  
✅ Accuracy Evaluation  
✅ Confusion Matrix  
✅ Feature Importance  
✅ Prediction on Custom Input  
✅ Model Saving using Joblib  

---

# 🧠 Machine Learning Algorithms Used

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- XGBoost Classifier

---

# 📂 Datasets Used

| Dataset | Purpose |
|---|---|
| Heart Disease Dataset | Predict heart disease |
| Diabetes Dataset | Predict diabetes |
| Breast Cancer Dataset | Predict cancer type |

---

# 📊 Project Workflow

## 1️⃣ Import Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## 2️⃣ Load Dataset

```python
df = pd.read_csv("dataset.csv")
```

## 3️⃣ Exploratory Data Analysis

- Missing value checking
- Correlation analysis
- Distribution plots
- Heatmaps

## 4️⃣ Data Preprocessing

- Feature scaling
- Train-test split
- Encoding
- Data cleaning

## 5️⃣ Train Machine Learning Models

```python
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier()
model.fit(X_train, y_train)
```

## 6️⃣ Model Evaluation

- Accuracy Score
- Precision
- Recall
- F1 Score
- ROC-AUC Score

## 7️⃣ Save Trained Model

```python
import joblib

joblib.dump(model, "disease_model.pkl")
```

---

# 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| Python | Programming |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Seaborn | Statistical Graphs |
| Scikit-Learn | Machine Learning |
| XGBoost | Boosting Algorithm |
| Joblib | Model Saving |
| Google Colab | Development |

---

# ▶️ Run in Google Colab

1. Upload notebook to Google Colab  
2. Upload datasets  
3. Run all cells sequentially  

---

# 📈 Output

- Prediction Results
- Accuracy Graphs
- Heatmaps
- ROC Curves
- Confusion Matrices
- Feature Importance Charts

---

# 💾 Saved Models

```python
model = joblib.load("heart_model.pkl")
```

---

# 🔮 Future Improvements

- Deep Learning Integration
- Streamlit Web App
- Flask API Deployment
- Real-time Prediction
- Cloud Deployment
- Explainable AI (XAI)

---

# 👨‍💻 Author

**Pabitra Pal**  
