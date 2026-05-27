# 👗 Clothing Fit Satisfaction Prediction Project

Machine Learning & Data Analysis Project using Rent the Runway dataset

---

## 📌 Project Overview

This project analyzes how users’ body information, clothing category, review text, and fit information affect clothing satisfaction.

The main objective is to predict whether a customer was satisfied or dissatisfied with the clothing fit using machine learning models.

Additionally, this project focuses on solving class imbalance problems and improving prediction performance for dissatisfied users.

---

## 🎯 Project Goals

- Predict clothing fit satisfaction (`fit_feedback`)
- Analyze relationships between:
  - body type
  - height / weight / BMI
  - bust size
  - clothing category
  - review text
  - actual fit
- Improve dissatisfied customer prediction performance
- Compare multiple machine learning models
- Visualize model performance clearly

---

## 📂 Dataset

Dataset: Rent the Runway Fit Reviews Dataset

Main Features:

| Feature | Description |
|---|---|
| body_type | User body shape |
| height | User height |
| weight | User weight |
| bust_size | Bust size |
| category | Clothing category |
| review_text | User review text |
| fit | Actual clothing fit |
| fit_feedback | Satisfaction label (Target) |

Target Variable:

- `0` = Dissatisfied
- `1` = Satisfied

---

## 🛠️ Tech Stack

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost
- Imbalanced-learn

---

## 📊 Data Analysis Process

### 1. Data Preprocessing
- Missing value handling
- BMI feature engineering
- Text preprocessing
- Encoding categorical variables

### 2. Exploratory Data Analysis (EDA)
- Satisfaction distribution
- Body type analysis
- Clothing category analysis
- Review keyword analysis

### 3. Machine Learning
Compared models:
- Logistic Regression
- Random Forest
- XGBoost

### 4. Imbalanced Data Handling
- Class Weight
- SMOTE
- Threshold optimization

### 5. Evaluation
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC

---

## 📈 Key Results

### ✔ Model Performance
- Improved dissatisfied class prediction
- Better recall performance for minority class
- Successfully identified important satisfaction factors

### ✔ Important Features
Top influential features:
- Rating
- BMI
- Review text keywords
- Clothing fit information
- Size-related terms

---

## 📷 Visualization Examples

### Confusion Matrix
![Confusion Matrix](sample_output/confusion_matrix.png)

### Feature Importance
![Feature Importance](sample_output/feature_importance.png)

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_ID/YOUR_REPOSITORY.git
```

### 2. Install Libraries

```bash
pip install -r requirements.txt
```

### 3. Run Notebook

Open:

```bash
data_project_final.ipynb
```

using:
- Google Colab
- Jupyter Notebook

---

## 📁 Project Structure

```bash
project/
│
├── data_project_final.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
├── sample_output/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│
└── data/
    ├── rtr_training.json
    └── rtr_test.json
```

---

## 📚 Future Improvements

- Deep Learning NLP models
- Recommendation system integration
- Real-time clothing fit prediction web service
- Personalized fashion recommendation

---

## 👨‍💻 Author

Park Cheolhan

Data Analysis Programming Project
2026