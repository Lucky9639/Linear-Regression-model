# Simple Linear Regression - Salary Prediction Model

This project demonstrates the implementation of a **Simple Linear Regression** model to predict an employee's salary based on their years of experience using Python and Scikit-Learn.

---

##  Dataset
The dataset contains two variables:
* **YearsExperience:** Independent variable ($X$) - Number of years of experience.
* **Salary:** Dependent variable ($Y$) - Annual salary 
* **Shape:** `(30, 2)`

---

##  Project Workflow
1. **Data Preprocessing:** Loaded `salary_data.csv` using Pandas.
2. **Train-Test Split:** Split data into Training set (80%) and Test set (20%).
3. **Model Training:** Fitted a `LinearRegression` model using `X_train` and `Y_train`.
4. **Prediction:** Evaluated model predictions on unseen test data (`X_test`).
5. **Model Evaluation:** Evaluated performance using Metrics ($R^2$ Score & RMSE).


