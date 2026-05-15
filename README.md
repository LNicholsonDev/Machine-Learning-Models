# Machine Learning Models

Supervised learning applied to classification and regression problems 
across healthcare, agriculture, finance, and business. Built and 
evaluated in Python using Scikit-learn and TensorFlow.

The healthcare models draw on biological domain knowledge in feature 
selection and result interpretation — clinical variables carry 
physiological interdependencies that shape which features are meaningful 
predictors and which are noise.

---

## Capstone: Crop Yield Prediction

The largest project in this repository. A decision tree model trained 
on historical agricultural data — region, rainfall, and temperature — 
to forecast crop yield.

| Metric | Score |
|---|---|
| Train R² | 0.978 |
| Test R² | 0.9579 |

Minimal degradation from training to test indicates strong 
generalization. Full feature analysis, methodology, and evaluation 
outputs are documented in the project folder.

[→ View Project](./Final%20Presentation%20-%20Decision%20Tree%20ML%20Model%20to%20Predict%20Crop%20Yield)

---

## All Models

| Project | Domain | Algorithm | Goal |
|---|---|---|---|
| [Crop Yield Prediction](./Final%20Presentation%20-%20Decision%20Tree%20ML%20Model%20to%20Predict%20Crop%20Yield) | Agriculture | Decision Tree | Forecast yield from region, rainfall, and temperature |
| [Heart Disease Classification](./Logistic%20Regression%20Model%20-%20Predict%20Heart%20Disease) | Healthcare | Logistic Regression | Classify patient likelihood of heart disease from clinical diagnostic features |
| [Diabetes Screening](./Naive%20Bayes%20ML%20Model%20-%20Predict%20Diabetes) | Healthcare | Naive Bayes | Predict diabetes diagnosis from patient health parameters |
| [Loan Repayment Prediction](./Decision%20Tree%20ML%20Model%20-%20Predict%20Loan%20Repayment) | Finance | Decision Tree | Predict repayment likelihood from credit history and financial behavior |
| [Customer Churn Prediction](./Neural%20Network%20ML%20Model%20-%20Predict%20Customer%20Churn) | Business | Neural Network | Identify customers at risk of churn to enable proactive retention |
| [Salary Prediction](./Linear%20Regression%20ML%20Model) | Business | Linear Regression | Predict compensation from years of experience as a regression baseline |

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Structure

Each model is self-contained in its own folder with a Jupyter notebook 
covering the full pipeline: exploratory analysis, preprocessing, 
train/test split, training, and evaluation with inline commentary and 
output visualizations.

The root directory also contains standalone NumPy, Matplotlib, and 
Seaborn exercises — library practice notebooks, distinct from the 
project work above.
