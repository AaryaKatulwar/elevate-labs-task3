# 🏠 Task 3: Linear Regression - Elevate AI/ML Internship

## 🎯 Objective

Build and evaluate a simple & multiple linear regression model to predict house prices using a given dataset.

---

## 📁 Dataset

**House Price Prediction Dataset**  
🔗 [Download Link]
(https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

---

## 🧰 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 📈 Workflow

### 1. Data Preprocessing

- Checked data types and null values.
- Encoded categorical column `furnishingstatus`.

### 2. Model Building

- Used `LinearRegression()` from `sklearn.linear_model`.
- Split data into train and test sets (80/20).
- Trained model using training data.

### 3. Evaluation Metrics

- **MAE**: Mean Absolute Error
- **MSE**: Mean Squared Error
- **R² Score**: Explained variance
- Also printed model **coefficients** for interpretation.

### 4. Visualization

- Scatter plot of **actual vs predicted** prices.

---

## 📊 Results

| Metric | Value |
|--------|-------|
| MAE    | 979679.69   |
| MSE    | 1771751116594.03   |
| R²     | 0.65   |

---

## 💡 Key Learnings

- Linear regression assumes linearity, homoscedasticity, and no multicollinearity.
- Coefficients represent the change in the target variable for one unit increase in the feature.
- R² score shows how much variance is explained by the model.

---

## 📎 File Structure

├── Housing.csv

├── linear_regression_task3.ipynb

├── README.md
