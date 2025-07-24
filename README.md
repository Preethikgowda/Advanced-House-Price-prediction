# 🏠 Advanced House Price Prediction using Machine Learning

This project aims to predict the final sale prices of residential homes using advanced regression techniques on a dataset containing detailed information about houses. The dataset used is from the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

---

## 🚀 Project Outcome

- Achieved high-accuracy price predictions by implementing machine learning algorithms.
- Performed extensive data preprocessing and feature engineering to improve model performance.
- Final model used **XGBoost Regressor** for top performance.

---

## 🧠 Technologies Used

- **Python** 🐍
- **Jupyter Notebook**
- **NumPy, Pandas** - Data wrangling
- **Matplotlib, Seaborn** - Visualization
- **Scikit-learn** - ML preprocessing & modeling
- **XGBoost** - Advanced regression model
- **Kaggle Dataset**

---

## 📊 Features in Dataset

- 80+ input variables including:
  - Lot size, year built, number of rooms, location-based features
  - Quality measures (e.g., overall quality, garage, basement conditions)
- Target variable:
  - `SalePrice` (House Price)

---

## 🔧 Project Workflow

1. **Data Cleaning**:
   - Missing values handling
   - Data type conversions

2. **Feature Engineering**:
   - Encoding categorical variables
   - Log transformation for skewed data
   - Feature scaling and correlation analysis

3. **Model Training**:
   - Train-Test split
   - Model comparison: Linear Regression, Ridge, Lasso, XGBoost
   - Final model: XGBoost with hyperparameter tuning

4. **Evaluation**:
   - RMSE (Root Mean Squared Error)
   - R² Score

---


## 📁 Project Structure

├── data/ # Raw and processed data files
├── notebooks/ # Jupyter notebooks for EDA & modeling
├── models/ # Trained model files (if any)
├── requirements.txt # Python dependencies
├── README.md # Project overview
└── house_price_prediction.ipynb # Main analysis notebook


## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Preethikgowda/Advanced-House-Price-Prediction.git
   cd Advanced-House-Price-Prediction
   ```
Install dependencies:

```bash
pip install -r requirements.txt
```
Launch the Jupyter notebook:
```
jupyter notebook
```

📚 Reference
Kaggle Competition: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

XGBoost Documentation: https://xgboost.readthedocs.io/en/stable/

🧑‍💻 Author
Preethi T K
preethikgowda26@gmail.com
