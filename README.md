# 🩺 Student Health Risk Prediction

A machine learning project developed for the **Kaggle Playground Series - Season 6 Episode 7** competition. The objective is to classify students into different health risk categories based on lifestyle and health-related attributes.

---

## 📌 Project Overview

This project predicts the **health condition** of students into one of three categories:

- At-Risk
- Unhealthy
- Fit

The solution includes data preprocessing, missing value handling, feature engineering, model training, evaluation, and Kaggle submission.

---

## 🎯 Objective

Develop a multiclass classification model to accurately predict student health conditions using machine learning techniques and improve prediction performance using model optimization.

---

## 📊 Dataset

Dataset Source:
- Kaggle Playground Series - Season 6 Episode 7
- Predicting Student Health Risk

Files:
- `train.csv`
- `test.csv`
- `sample_submission.csv`

Target Variable:
- `health_condition`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- Google Colab
- Kaggle

---

## 🔄 Machine Learning Workflow

- Data Loading
- Data Cleaning
- Missing Value Imputation
- Categorical Feature Processing
- Train/Test Split
- Model Training
- Balanced Accuracy Evaluation
- Kaggle Submission Generation

---

## 🤖 Models Used

### Random Forest Classifier
- Baseline model
- Used for initial benchmarking

### CatBoost Classifier
- Optimized for categorical features
- Improved prediction performance
- Used for final Kaggle submission

---

## 📈 Evaluation Metric

The competition evaluates submissions using:

**Balanced Accuracy Score**

This metric is suitable for multiclass classification problems where class distributions may not be perfectly balanced.

---

## 📂 Project Structure

```
Student-Health-Risk-Prediction/
│
├── Student_Health_Risk_Prediction.ipynb
├── train.csv
├── test.csv
├── sample_submission.csv
├── submission.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Student-Health-Risk-Prediction.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
Student_Health_Risk_Prediction.ipynb
```

4. Run all cells.

---

## 📌 Skills Demonstrated

- Data Preprocessing
- Feature Engineering
- Machine Learning
- Classification
- CatBoost
- Random Forest
- Model Evaluation
- Kaggle Competition Workflow

---

## 👩‍💻 Author

**Vaishnavi Naik**

GitHub: https://github.com/Vaisshhh55


## ⭐ Acknowledgements

- Kaggle Playground Series
- Scikit-learn
- CatBoost
