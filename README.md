# LoanPrediction
# 🏦 Loan Eligibility Prediction

This project aims to predict whether a loan application will be approved based on a variety of applicant features. It was built as a part of a machine learning portfolio to demonstrate skills in data preprocessing, classification modeling, and model evaluation.

---

## 📊 Dataset

- Source: [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/)
- The dataset contains information about loan applicants such as gender, income, loan amount, credit history, and more.

---

## 🎯 Objective

To build a machine learning model that can predict whether a loan should be approved (`Y`) or not (`N`) based on the applicant's details.

---

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** for data manipulation
- **Matplotlib** & **Seaborn** for data visualization
- **Scikit-learn** for machine learning models

---

## 🔧 Data Preprocessing

- Missing values were imputed using **mean** and **median** strategies.
- Categorical variables were encoded appropriately.
- Feature selection and data cleaning steps were applied before training.

---

## 🤖 Models Trained

Three classification models were trained and compared:

1. **Random Forest Classifier**
2. **Decision Tree Classifier**
3. **Naive Bayes Classifier**

---

## 🏆 Results

- After training and evaluating all three models, **Naive Bayes** showed the best performance in terms of accuracy on the test data.
- Evaluation metrics such as accuracy, precision, and recall were considered.

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
- Handling class imbalance (SMOTE, class weights)
- Deployment via Streamlit or Flask

---

## 📁 Project Structure

```bash
LoanEligibilityPrediction/
│
├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks for EDA & modeling
├── LoanPrediction.py     # Script version of the ML pipeline
├── requirements.txt      # Python dependencies (optional)
└── README.md             # Project documentation (this file)

