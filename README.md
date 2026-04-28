# 🤖 AI/ML Engineering Internship — DevelopersHub Corporation

**Intern:** [Your Name]  
**Due Date:** 28 April, 2026  
**Tasks Completed:** 4 out of 6

---

## 📋 Tasks Overview

| # | Task | Dataset | Model(s) | Status |
|---|------|---------|----------|--------|
| 1 | Iris Dataset EDA & Visualization | Iris (seaborn built-in) | Exploratory Analysis | ✅ Complete |
| 2 | Stock Price Prediction | Apple AAPL (yfinance) | Linear Regression, Random Forest | ✅ Complete |
| 3 | Heart Disease Prediction | UCI Heart Disease | Logistic Regression, Decision Tree | ✅ Complete |
| 6 | House Price Prediction | California Housing (sklearn) | Linear Regression, Gradient Boosting, Random Forest | ✅ Complete |

---

## 📁 Repository Structure

```
├── Task1_Iris_EDA.ipynb           # Iris dataset exploration & visualization
├── Task2_Stock_Prediction.ipynb   # AAPL stock price prediction
├── Task3_Heart_Disease.ipynb      # Heart disease classification
├── Task6_House_Price.ipynb        # House price regression
└── README.md
```

---

## 📊 Task 1: Iris Dataset EDA

**Objective:** Load, inspect, and visualize the Iris dataset to understand data trends.

**Dataset:** Iris Dataset (150 samples, 4 features, 3 species)

**Key Steps:**
- Loaded dataset using seaborn
- Inspected shape, dtypes, and summary statistics
- Created scatter plots, histograms, box plots, pair plots, violin plots, and a correlation heatmap

**Key Findings:**
- Petal length & width are the most discriminative features for species classification
- Setosa is completely linearly separable from the other two species
- Petal length and petal width have a very high correlation (0.96)

---

## 📈 Task 2: Stock Price Prediction

**Objective:** Predict the next day's closing price for Apple (AAPL) stock.

**Dataset:** Yahoo Finance via `yfinance` library (2020–2024)

**Models Applied:**
- Linear Regression
- Random Forest Regressor

**Feature Engineering:**
- 5-day & 10-day moving averages
- Daily percentage change
- High-Low daily range

**Key Results:**
- Random Forest outperformed Linear Regression
- Moving averages were the most important predictors
- Model achieved high R² score on test set

---

## ❤️ Task 3: Heart Disease Prediction

**Objective:** Classify whether a patient is at risk of heart disease.

**Dataset:** UCI Heart Disease Dataset (Cleveland) — 303 patients, 13 features

**Models Applied:**
- Logistic Regression
- Decision Tree Classifier

**Evaluation Metrics:**
- Accuracy, AUC-ROC, Confusion Matrix, Classification Report

**Key Findings:**
- Chest pain type (cp) is the strongest predictor of heart disease
- Maximum heart rate (thalach) is inversely correlated with disease risk
- ST depression (oldpeak) is a significant risk indicator
- Models achieved ~80%+ accuracy

---

## 🏠 Task 6: House Price Prediction

**Objective:** Predict median house prices using property and demographic features.

**Dataset:** California Housing Dataset (20,640 properties, 8 features)

**Models Applied:**
- Linear Regression
- Gradient Boosting Regressor
- Random Forest Regressor

**Evaluation Metrics:**
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

**Key Findings:**
- Median income is the #1 predictor of house value
- Geographic location (Latitude/Longitude) has high importance
- Gradient Boosting achieved the best performance (R² ≈ 0.84)
- Feature engineering (RoomsPerPerson) improved predictions

---

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** — data loading and manipulation
- **numpy** — numerical computing
- **matplotlib / seaborn** — data visualization
- **scikit-learn** — ML models and evaluation
- **yfinance** — stock data API
- **Jupyter Notebook** — interactive development

## ⚙️ Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yfinance jupyter
```

## 🚀 Running the Notebooks

```bash
jupyter notebook
```
Then open any `.ipynb` file and run all cells in order.

---

*DevelopersHub Corporation — AI/ML Engineering Internship, 2026*
