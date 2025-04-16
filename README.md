# 🚢 Titanic Survival Prediction - Machine Learning Project

This project is a solution to the classic Titanic dataset problem on Kaggle.  
It predicts whether a passenger survived the Titanic shipwreck based on features like age, sex, class, and more.

---

## 📌 Problem Statement
Use machine learning to create a model that predicts which passengers survived the Titanic tragedy.

---

## 📊 Dataset
- **train.csv**: Training data with labels (`Survived`)
- **test.csv**: Test data without labels (to predict)
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

## 💼 Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🧠 Workflow

### 1. Exploratory Data Analysis (EDA)
- Identified null values and feature distributions
- Key patterns:
  - Women had higher survival rates
  - 1st class passengers had higher chances of survival

### 2. Data Cleaning
- Filled missing values (`Age`, `Embarked`, `Fare`)
- Dropped unnecessary columns (`Cabin`, `Ticket`, `Name`)

### 3. Feature Encoding
- Converted categorical data:
  - `Sex`: male → 0, female → 1
  - `Embarked`: S → 0, C → 1, Q → 2

### 4. Model Building
- Used **Logistic Regression** for classification
- Trained on key features like `Pclass`, `Sex`, `Age`, etc.

### 5. Prediction
- Made predictions on test data
- Output saved in `submission.csv` for Kaggle submission

---

## 🔍 How to Run the Project

1. Clone the repo:
   ```bash
   git clone https://github.com/ompajgade/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
