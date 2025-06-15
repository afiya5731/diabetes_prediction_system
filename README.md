# 🩺 Diabetes Prediction using Machine Learning

This project aims to predict the likelihood of diabetes in individuals based on various health and lifestyle features. It leverages machine learning techniques—specifically **Logistic Regression**—to analyze inputs like age, BMI, glucose levels, and family history, delivering accurate and interpretable predictions.

## 💡 Motivation

Diabetes is a major global health issue, and early detection is critical for prevention and management. Traditional methods often rely on limited data and manual diagnosis. Our system uses ML to enhance prediction accuracy and accessibility, even for users with limited medical or technical background.

## ⚙️ Features

- Logistic Regression model for binary classification
- Data preprocessing: handling missing values, normalization, encoding
- Easy-to-use web interface built with Flask
- Real-time prediction results based on user input
- Actionable insights and recommendations for diabetes prevention

## 📊 Dataset

- Source: [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Features include:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (Label)

## 🧠 ML Model

- **Algorithm**: Logistic Regression
- **Accuracy**: ~84%
- **Libraries**: `scikit-learn`, `pandas`, `numpy`, `matplotlib`

## 🖥️ Tech Stack

- Python
- Flask (for backend and deployment)
- HTML/CSS/JS (for frontend)
- Jupyter Notebook (for experimentation and analysis)

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction-ml.git
   cd diabetes-prediction-ml
