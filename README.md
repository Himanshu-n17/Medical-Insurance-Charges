
---

## 📊 Dataset

The dataset contains the following columns:

- `age`: Age of the individual
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of children covered by insurance
- `smoker`: Smoking status
- `region`: Residential region
- `charges`: Annual medical insurance charges (target variable)

---

## 🧰 Technologies Used

- **Python 3**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn, Plotly** – Data visualization
- **Scikit-learn** – Linear regression modeling

---

## 🧪 Exploratory Data Analysis (EDA)

The EDA covers:

- **Histograms & Boxplots**: Distribution of age, BMI, and charges
- **Scatter Plots**: Relationship of `charges` with `age`, `bmi`, and `smoker` status
- **Correlation Analysis**: Numeric + categorical correlation with charges
- **Cluster Patterns**: Identified smoker/non-smoker cost behavior

---

## 📈 Linear Regression Models

1. **Simple Linear Regression**: Using `age` to predict `charges` (non-smokers only)
2. **Multiple Linear Regression**: Using `age`, `bmi`, and `children` as features
3. **Categorical Encoding**: Transformed `smoker`, `region`, etc., into numeric format for full-model regression
4. **Model Evaluation**: Used RMSE (Root Mean Squared Error) as loss metric

---

## 📈 Regression Models

The project walks through several stages of linear regression:

### 1. Linear Regression with One Feature
- Predict charges based on age for non-smokers
- Visual fitting using custom functions
- Root Mean Squared Error (RMSE) used as a loss metric

### 2. Linear Regression with Scikit-learn
- Train `LinearRegression()` model using `age` as input
- Predict charges and calculate RMSE
- Visualize regression line vs actual data

### 3. Multiple Linear Regression
- Include `age`, `bmi`, and `children` as input features
- Analyze improvements in RMSE
- Visualize impact of BMI and children

### 4. Categorical Variable Handling
- Encode categorical features like `smoker` and `sex` into numerical format
- Extend regression model to handle entire dataset, including categorical features

---

## 📌 Key Insights

- Smoking significantly increases charges, especially with high BMI.
- Age positively correlates with charges.
- BMI alone doesn't predict charges well unless combined with other risk factors.

---
