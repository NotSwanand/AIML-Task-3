# 📈 House Price Prediction – Linear Regression

## 📌 Objective
The goal of this task is to implement and understand simple and multiple linear regression using a real-world housing dataset. The model predicts house prices based on features like area, bedrooms, bathrooms, and more.

---

## 📁 Dataset
- **Source**: [Kaggle – Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- **File Used**: `Housing.csv`

---

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Scikit-learn (Linear Regression, train-test split, evaluation metrics)
- Seaborn, Matplotlib (for data visualization)

---

## ✅ Steps Performed

### 1. Data Loading & Inspection
- Loaded the CSV file and verified no missing values.
- Identified 7 categorical features to be encoded.

### 2. Data Preprocessing
- Converted all categorical features into numeric using **one-hot encoding** with `pd.get_dummies()`.
- Verified all features are numeric before model training.

### 3. Feature Selection & Splitting
- Defined `X` (features) and `y` (target = price).
- Split data into **80% training** and **20% testing** using `train_test_split()`.

### 4. Model Training
- Trained a **Linear Regression** model using `LinearRegression()` from `sklearn`.

### 5. Model Evaluation
- Generated predictions and evaluated using:
  - **MAE** (Mean Absolute Error)
  - **MSE** (Mean Squared Error)
  - **RMSE** (Root Mean Squared Error)
  - **R² Score** (Coefficient of Determination)

### 6. Interpretation
- Displayed the model’s **intercept** and **feature coefficients**.
- Analyzed which features had the most influence on price.

### 7. Visualization
- Plotted **Actual vs Predicted** prices using scatter plot and a reference line.

---

## 📊 Key Metrics
- **MAE**: 970,043.40
- **MSE**: 1,754,318,687,330.66
- **RMSE**: 1,324,506.96
- **R² Score**: 0.65

---

## 📂 Files Included
- `house_price_regression.ipynb` – Jupyter notebook with complete implementation
- `Housing.csv` – Dataset file used
- `README.md` – Project summary and documentation

---

## 📝 Submission
This project was completed as part of the **AI & ML Internship**  
**Task 3: Linear Regression – Predicting House Prices**

