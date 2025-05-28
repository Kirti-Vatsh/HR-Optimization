# HR-Optimization
A data-driven solution for predicting employee churn at Seagate using machine learning and analytics. This project leverages Python, R, and Excel to clean, analyze, and model employee data, helping HR teams make informed workforce planning decisions.

## Problem Statement
Employee turnover costs can range from 50% to 200% of an employee's annual salary. Our goal is to build a predictive model that identifies employees at risk of voluntary churn, enabling Seagate's HR team to:

* Forecast a two-year hiring pipeline
* Optimize workforce strategies
* Minimize financial impact (~$43.6M projected churn costs)

## Project Highlights

✅ Cleaned and prepared a 25,995-row dataset across 27 countries and 82 locations.
✅ Handled missing data, outliers, and normalized compensation data.
✅ Engineered features from HR data (e.g., tenure, compa ratio, generation).
✅ Built multiple ML models:

* Random Forest (Best model: 82% accuracy)
* Logistic Regression
* KNN-5, KNN-10
* AdaBoost
* Bagging Classifier

✅ Delivered actionable insights:

* Engineering teams → 114% higher churn risk
* Asia-Pacific → 1.8x more likely to churn
* Thailand → 31% higher churn than USA

## Tools & Technologies

| 📊 Data        | 🧠 Modeling                          | 📈 Visualization                     |
|----------------|-------------------------------------|--------------------------------------|
| Excel          | Python (scikit-learn, pandas)       | Tableau, Python (matplotlib, seaborn)|
| R              | Random Forest                        | Matplotlib, Seaborn                   |
| Jupyter        |                                     |                                      |

## Files in This Repository

| File                          | Description                                    |
|------------------------------|------------------------------------------------|
| SeagateCorr_4.ipynb          | Jupyter notebook for churn prediction models   |
| DataCleanupReport.docx       | Detailed data cleaning steps                   |
| PreliminaryDataReport.pdf    | Initial exploration & insights                 |
| PresentationNotes.pdf        | Final presentation with key takeaways          |
| ProductBacklog.pdf           | Agile product backlog                          |
