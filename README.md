# Boston-house-price-prediction
Machine Learning project predicting Boston house prices

# 🏠 Boston House Price Prediction

This project predicts the **median value of houses** in Boston suburbs using machine learning models.  
It involves data cleaning, feature analysis, model training, and evaluation of regression models.

---

## 📊 Dataset Information

- **File Used:** `HousingData.csv`  
- **Rows:** 506  
- **Columns:** 14  
- **Target Variable:** `MEDV` – Median value of owner-occupied homes (in $1000s)

| Feature | Description |
|----------|--------------|
| CRIM | Per capita crime rate by town |
| ZN | Proportion of residential land zoned for lots over 25,000 sq.ft. |
| INDUS | Proportion of non-retail business acres per town |
| CHAS | Charles River dummy variable (1 if tract bounds river; 0 otherwise) |
| NOX | Nitric oxides concentration (parts per 10 million) |
| RM | Average number of rooms per dwelling |
| AGE | Proportion of owner-occupied units built prior to 1940 |
| DIS | Weighted distances to five Boston employment centres |
| RAD | Index of accessibility to radial highways |
| TAX | Full-value property-tax rate per $10,000 |
| PTRATIO | Pupil-teacher ratio by town |
| B | 1000(Bk - 0.63)^2 where Bk is the proportion of Black people by town |
| LSTAT | % lower status of the population |
| MEDV | Median value of owner-occupied homes (Target) |

---

## ⚙️ Steps Involved

1. **Data Preprocessing**
   - Handled missing values  
   - Checked data types and distribution  
   - Normalized/standardized where necessary  

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix  
   - Scatter plots between features and target  

3. **Model Building**
   - **Linear Regression**  
   - **Random Forest Regressor**

4. **Model Evaluation**
   - **Linear Regression**
     - MSE: `25.01`
     - R²: `0.65`
   - **Random Forest**
     - MSE: `8.22`
     - R²: `0.88`

5. **Feature Importance**
   - Found key predictors like `RM`, `LSTAT`, and `NOX`.

---

## 🧠 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sathvika246/Boston-house-price-prediction.git
