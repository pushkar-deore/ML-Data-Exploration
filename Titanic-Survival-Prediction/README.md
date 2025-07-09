# 🚢 Titanic Survival Prediction

This machine learning project predicts the survival of passengers aboard the Titanic using logistic regression and random forest classifiers. It applies classification techniques to a real-world dataset to determine survival outcomes based on features like age, gender, class, and fare.

---

## 📌 Problem Statement

Can we predict whether a passenger survived the Titanic disaster based on available information such as:

- Passenger class
- Sex
- Age
- Number of siblings/spouses aboard
- Fare paid
- Embarkation port

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for EDA and plotting)
- Scikit-learn (for preprocessing and model training)

---

## 📊 Workflow Overview

1. **Data Loading**
   - Dataset: Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic/data)
   - Loaded using Pandas

2. **Exploratory Data Analysis (EDA)**
   - Visualized survival distribution, class-wise survival, and gender-based patterns
   - Identified missing values and distributions

3. **Data Preprocessing**
   - Handled missing values (e.g., `Age`, `Embarked`)
   - Converted categorical features using `LabelEncoder`
   - Dropped irrelevant features (`PassengerId`, `Name`, `Ticket`, `Cabin`)

4. **Model Building**
   - Logistic Regression
   - Random Forest Classifier

5. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## ✅ Results

| Model                  | Accuracy  |
|------------------------|-----------|
| Logistic Regression    | 79.78%    |
| Random Forest Classifier | 81.56% |

📌 **Random Forest performed better** in this case.

---

## 📁 Project Files

- `titanic_survival_prediction.ipynb` — Full notebook with code, preprocessing, model training, and evaluation.
- `README.md` — Project documentation.

---

## 🧠 Learning Outcome

- Understanding of binary classification
- Real-world data preprocessing and cleaning
- Feature encoding and model comparison
- How to evaluate classification models with confusion matrix & metrics

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Try other models like XGBoost, SVM
- Create a web app with Streamlit for user input prediction
- Feature engineering (e.g., family size, titles from names)

---

## 📚 Dataset Source

[Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)

---

Feel free to fork this repo, explore the notebook, and suggest improvements!
