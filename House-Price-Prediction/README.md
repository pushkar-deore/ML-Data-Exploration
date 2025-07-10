# 🏠 House Price Prediction (California Housing Dataset)

This machine learning project predicts median house prices in California districts using the California Housing Dataset from Scikit-learn. It applies linear regression to explore how features like income, population, and house age influence housing prices.

---

## 📌 Problem Statement

Build a regression model to predict **median house value** based on the following features:
- Median income
- Average house age
- Total rooms
- Total bedrooms
- Population
- Households
- Latitude & Longitude

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for EDA)
- Scikit-learn (for dataset and model building)

---

## 📊 Workflow

1. **Dataset Import**
   - Loaded California Housing Dataset from `sklearn.datasets.fetch_california_housing()`

2. **Exploratory Data Analysis (EDA)**
   - Checked correlations and distributions
   - Visualized relationships between features and target
   - Observed how `MedInc` and `AveRooms` strongly correlate with house value

3. **Preprocessing**
   - No missing values in the dataset
   - Scaled features (if needed)

4. **Modeling**
   - Applied **Linear Regression**
   - Split data into training and testing sets (80/20)

5. **Evaluation**
   - Metrics used:
     - R² Score
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)

---

## ✅ Results

- **R² Score**: ~0.61  
- **RMSE**: ~0.72 (indicating moderate prediction accuracy)

📌 **Median Income** was the strongest predictor of house price.

---

## 📁 Project Files

- `house_price_prediction.ipynb` — Notebook with all code, EDA, and model evaluation
- `README.md` — This project documentation

---

## 🧠 Learning Outcomes

- Real-world regression with a built-in dataset
- Understanding the influence of socio-economic factors on housing prices
- Interpreting regression metrics
- Data visualization for insight generation

---

## 🚀 Future Enhancements

- Try other algorithms (Random Forest, XGBoost)
- Perform feature scaling and engineering
- Use log-transform for skewed features
- Deploy with Streamlit or Flask

---

## 📚 Dataset Source

- **California Housing Dataset** from Scikit-learn  
  ([Documentation link](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html))

---

Feel free to fork, explore, and build on this project!

