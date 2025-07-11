# ❤️ Heart Disease Prediction (Machine Learning Project)

This project uses machine learning models to predict whether a person is likely to have heart disease based on medical attributes. It’s built using the UCI Heart Disease dataset and includes exploratory data analysis, classification, and feature importance interpretation.

---

## 📌 Project Overview

- **Goal**: Predict the presence of heart disease in patients using classification algorithms.
- **Dataset**: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Type**: Binary Classification (`1 = disease`, `0 = no disease`)
- **Tools**: Python, Pandas, Seaborn, Scikit-learn, Matplotlib
- **Algorithms**: Logistic Regression, Decision Tree

---

## 📁 Dataset Description

| Feature | Description |
|--------|-------------|
| `age` | Age of the patient |
| `sex` | Gender (1 = male; 0 = female) |
| `cp` | Chest pain type (0 to 3) |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol in mg/dl |
| `fbs` | Fasting blood sugar > 120 mg/dl |
| `restecg` | Resting ECG results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression |
| `slope` | Slope of ST segment |
| `ca` | Number of major vessels (0–3) |
| `thal` | Thalassemia (0, 1, 2) |
| `target` | 0 = no disease, 1 = disease |

---

## 🧠 Machine Learning Workflow

### 1. Data Preprocessing
- Checked for missing values and cleaned non-numeric entries (e.g., '?')
- Converted categorical features if necessary
- Scaled features using `StandardScaler`
- Split data into train and test sets (80/20)

### 2. Exploratory Data Analysis (EDA)
- Plotted distributions and relationships (Seaborn & Matplotlib)
- Correlation heatmap to identify key features

### 3. Model Building
- **Logistic Regression**
- **Decision Tree Classifier**

### 4. Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Feature importance from Decision Tree

---

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ✅ 79% |
| Decision Tree | ✅ 98% |

> Feature Importance Highlights:
- `cp` (Chest Pain Type)
- `thal`
- `ca`
- `oldpeak`
- `thalach`

---

## 📌 Key Learnings

- How to handle and preprocess real-world medical data
- Building and evaluating classification models
- Understanding feature importance in decision trees
- Visualizing insights with Seaborn and Matplotlib

---

## ✅ Future Improvements

- Add more models (Random Forest, SVM, XGBoost)
- Perform Hyperparameter tuning (GridSearchCV)
- Use SHAP or LIME for interpretability
- Deploy as a web app (Streamlit or Flask)

---

## 🙌 Acknowledgements

- Dataset: UCI via [Kaggle](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- Tools: Scikit-learn, Pandas, Matplotlib, Seaborn

---

## 🔗 Connect

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/pushkar--deore-/) or check out my other ML projects on [GitHub](https://github.com/pushkar-deore/ML-Data-Exploration).



