# 📘 Math Score Predictor

A machine learning project that predicts students' math scores based on demographic and academic features using linear regression.

---

## 📌 Project Overview

This project builds a regression model to predict the `math_score` of students using a combination of demographic data and scores from other subjects. It explores the relationships between reading, writing, and math performance, and demonstrates how feature selection impacts model accuracy.

---

## 🎯 Objectives

- Analyze correlations between math, reading, and writing scores
- Build a linear regression model to predict math scores
- Evaluate how different features affect prediction accuracy

---

## 🗂️ Project Structure

math_score_predictor/
│
├── data/
│   └── StudentsPerformance.csv
│
├── visuals/
│   ├── correlation_heatmap.png
│   ├── math_score_distribution.png
│   └── predictions_distribution.png
│
├── notebooks/
│   └── analysis.ipynb
│
├── models/
│   └── math_score_model.pkl
│
├── README.md
└── requirements.txt

---

## 🧪 Features Used

| Feature | Description |
|--------|-------------|
| `gender` | Student's gender |
| `race/ethnicity` | Ethnic group |
| `parental_level_of_education` | Parent's education level |
| `lunch` | Type of lunch received |
| `test_preparation_course` | Whether test prep was completed |
| `reading_score` | Score in reading |
| `writing_score` | Score in writing |

---

## 🧠 Technologies

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 📈 Model Performance

| Metric | Value |
|--------|-------|
| MAE    | 4.21  |
| MSE    | 29.10 |
| R²     | 0.88  |

The model achieves high accuracy when combining demographic features with reading and writing scores.

---

## 📌 Key Insights
- Reading and writing scores are highly correlated with math performance
- Demographic features alone are weak predictors
- Combining academic and demographic data yields the best results

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/404-Not-Found-create/predicting_math_scores_based_on_linear_regression
   cd math-score-predictor

2. Install dependencies:
    pip install -r requirements.txt

3. Launch the notebook:
    jupyter notebook notebook/regression_model.ipynb