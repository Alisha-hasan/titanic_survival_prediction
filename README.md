# titanic_survival_prediction
Titanic survival prediction is a classic machine learning classification problem
# 🚢 Titanic Survival Prediction using Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yhGii3LeqH45Xyv7FjKFPzFCagoX0PIP?usp=sharing)  

---
## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using **Machine Learning (Logistic Regression)**.
The model is trained on the famous Titanic dataset and uses features like age, gender, class, and family size.

---

## 🎯 Objective

To build a classification model that predicts:

> **Survival (1) or Not Survived (0)**

---

## 📂 Dataset

* Dataset used: `train.csv` (Titanic dataset)
* Source: Kaggle Titanic Dataset

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas (Data Processing)
* NumPy
* Scikit-learn (Machine Learning)
* Matplotlib & Seaborn (Visualization)

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Handled missing values:

  * `Age` → filled with median
  * `Embarked` → filled with "S"
* Converted categorical data:

  * `Sex` → male=0, female=1
  * `Embarked` → S=0, C=1, Q=2
* Feature Engineering:

  * Created `Family_size = SibSp + Parch`
  * Converted `Cabin` to binary (0/1)
* Dropped unnecessary columns:

  * Name, Ticket, PassengerId

---

### 2. Model Building

* Algorithm used: **Logistic Regression**
* Data split:

  * 80% Training
  * 20% Testing

---

### 3. Model Evaluation

* Accuracy Score
* Confusion Matrix (visualized using heatmap)

---

## 📊 Results

* Achieved accuracy: **~75%–85%**
* Model performs well in predicting survival based on given features
## my project
https://colab.research.google.com/drive/1yhGii3LeqH45Xyv7FjKFPzFCagoX0PIP?usp=sharing

## 🧠 Key Learnings

* Importance of data cleaning and preprocessing
* Handling missing values
* Converting categorical data into numerical format
* Model evaluation techniques

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-ml-project.git
```

2. Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3. Run the script:

```bash
python main.py
```

---

## 📌 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Feature scaling
* Cross-validati

---

## ⭐ Acknowledgment

* Kaggle for providing the dataset
* Scikit-learn documentation
