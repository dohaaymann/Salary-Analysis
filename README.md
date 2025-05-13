
# SalaryPredictor-ML

A data science and machine learning project that analyzes and predicts salaries based on professional and job-related attributes. This project explores a cleaned salary dataset to uncover trends and builds various regression models to predict salaries.

## 🧹 Data Cleaning & Preparation
- Introduced and handled missing values and duplicates
- Standardized job titles and other categorical values
- Removed outliers using IQR method
- Encoded categorical features

## 📈 Machine Learning Models Used
The following regression models were trained and evaluated:
- `LinearRegression`
- `RandomForestRegressor`
- `DecisionTreeRegressor`
- `KNeighborsRegressor`
- `Lasso`
- `Ridge`
- `SVR (Support Vector Regression)`

## 🧪 Evaluation
Models were evaluated using metrics such as:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## 📊 Dataset
The dataset includes the following features:
- `work_year`
- `experience_level`
- `employment_type`
- `job_title`
- `salary_in_usd`
- `employee_residence`
- `remote_ratio`
- `company_location`
- `company_size`
  
## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn


- Jupyter Notebook
