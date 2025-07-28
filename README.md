# 🧠 Breast Cancer Prediction using Machine Learning

A machine learning project focused on predicting whether a breast tumor is **Malignant (M)** or **Benign (B)** using various classification algorithms. 🧬 The primary goal is to assist early diagnosis of breast cancer through data-driven models.

## 🚀 Project Overview

In this project, I applied and compared five machine learning algorithms to classify breast cancer tumors:

- 🌲 **Decision Tree (DT)**
- 📈 **Logistic Regression (LG)**
- 🔍 **Support Vector Machine (SVM)**
- 🧪 **Naive Bayes (NB)**
- 🌳 **Random Forest (RF)**

After training and testing each model, **SVM** achieved the highest accuracy of **97%**, making it the best performer for this dataset. ✅

## 🧰 Technologies & Tools Used

- 🐍 **Python**
- 📊 **Pandas, NumPy** – for data manipulation
- 📉 **Scikit-learn (sklearn)** – for ML models and preprocessing
- 📈 **Matplotlib, Seaborn** – for data visualization
- 💻 **Jupyter Notebook / VS Code** – for development
- 📁 **CSV Dataset** – Breast Cancer Dataset (from [Kaggle](https://www.kaggle.com/))

## 📚 Dataset

The dataset contains various features related to tumor characteristics such as:

- Radius, Texture, Perimeter, Area
- Smoothness, Compactness, Concavity, Symmetry
- Diagnosis Label: `M = Malignant`, `B = Benign`

## 📌 Model Performance Summary

| Model              | Accuracy |
|-------------------|----------|
| Decision Tree      | 92%      |
| Logistic Regression| 95%      |
| SVM (Best 🎯)      | **97%**  |
| Naive Bayes        | 93%      |
| Random Forest      | 96%      |

## 📈 Confusion Matrix & Metrics

All models were evaluated using:
- ✅ **Accuracy**
- 📉 **Confusion Matrix**
- 🔍 **Precision, Recall, F1-score**

## 🧪 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/breast-cancer-prediction.git
   cd breast-cancer-prediction

