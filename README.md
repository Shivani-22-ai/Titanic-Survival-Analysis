# Titanic Survival Prediction using Machine Learning

## Project Overview

This project explores the Titanic dataset and applies machine learning techniques to predict passenger survival. The project covers the complete machine learning workflow, including data exploration, data cleaning, feature engineering, model training, model evaluation, and model comparison.

The objective is to identify the factors that influenced survival and build predictive models capable of estimating whether a passenger would survive the Titanic disaster.

---

## Dataset

The dataset contains passenger information such as:

* Passenger Class (Pclass)
* Name
* Sex
* Age
* Fare
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Embarked Location
* Survival Status

Target Variable:

* **Survived**

  * 0 = Did Not Survive
  * 1 = Survived

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

### 1. Titanic_Survival_Analysis.ipynb

This notebook focuses on Exploratory Data Analysis (EDA).

Topics covered:

* Dataset exploration
* Missing value analysis
* Data cleaning
* Feature engineering
* Survival analysis
* Data visualization
* Key findings and insights

### 2. Titanic_Survival_Prediction.ipynb

This notebook focuses on Machine Learning.

Topics covered:

* Data preprocessing
* Feature selection
* Train-Test Split
* Model training
* Model evaluation
* Model comparison
* Performance analysis

---

## Feature Engineering

The following features were created to improve model performance:

### Family_Size

Family_Size = SibSp + Parch

This feature represents the number of family members traveling with a passenger.

### Age_Group

Passengers were categorized into age groups:

* Child
* Young Adult
* Middle Aged
* Senior

---

## Machine Learning Models Evaluated

| Model                     | Accuracy |
| ------------------------- | -------- |
| Logistic Regression       | 80%      |
| Random Forest Classifier  | 80%      |
| Decision Tree Classifier  | 76%      |
| K-Nearest Neighbors (KNN) | 71%      |

---

## Key Findings

* Female passengers had a significantly higher survival rate than male passengers.
* First-class passengers were more likely to survive than passengers in lower classes.
* Family size showed a relationship with survival probability.
* Age and fare also influenced survival outcomes.
* Logistic Regression and Random Forest achieved the highest prediction accuracy among the evaluated models.

---

## Conclusion

This project demonstrates a complete end-to-end machine learning workflow using Python and Scikit-Learn.

The analysis shows that passenger characteristics such as gender, passenger class, age, fare, and family size play an important role in predicting survival.

Among the evaluated models, Logistic Regression and Random Forest produced the best performance with an accuracy of approximately 80%.

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Feature scaling
* Additional feature engineering
* Advanced ensemble models
* Deployment using Streamlit or Flask

---

## Author

**Shivani Lokinindi**

