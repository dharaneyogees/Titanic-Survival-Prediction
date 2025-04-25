# 🚢 Titanic Survival Prediction – A Machine Learning Project

This project is built around the famous Titanic dataset to explore passenger data and predict survival using a machine learning classification model.

## 🎯 Objective

The goal was to develop a predictive model that can determine whether a passenger survived the Titanic disaster based on features like age, gender, passenger class, fare, and port of embarkation. The project emphasizes data preprocessing, model development, and performance evaluation.

---

## 📊 Dataset Information

The dataset contains the following key features:
- `Pclass` – Ticket class (1st, 2nd, 3rd)
- `Sex` – Gender of the passenger
- `Age` – Age in years
- `SibSp`, `Parch` – Number of siblings/spouses/parents aboard
- `Fare` – Ticket price
- `Embarked` – Port of Embarkation (C, Q, S)
- `Survived` – Target variable (0 = No, 1 = Yes)

---

## 🧪 What I Did

- **Exploratory Data Analysis (EDA)** to understand trends.
- **Handled missing values** in columns like `Age` and `Embarked`.
- **Encoded categorical variables** like `Sex` and `Embarked`.
- **Feature selection** based on correlation and relevance.
- **Trained a Random Forest classifier** for binary classification.
- **Evaluated performance** using Accuracy, Precision, Recall, and Confusion Matrix.
- **Visualized insights** using seaborn and matplotlib.

---

## 📈 Model Performance

The model achieved strong predictive performance using the Random Forest algorithm. Evaluation metrics like accuracy, precision, recall, and F1-score were calculated to validate the model.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
