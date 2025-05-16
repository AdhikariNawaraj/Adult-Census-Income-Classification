# Adult-Census-Income-Classification

Project Overview:
This project predicts whether an individual's income exceeds $50K/year using demographic and work-related attributes. We use the Adult Census Income dataset from the UCI Machine Learning Repository and apply multiple classification models to uncover insights into income inequality and build accurate prediction systems.

🧠 Objectives:
Understand how attributes like education, age, and hours worked influence income.
Apply machine learning models to classify income levels.
Evaluate and compare model performance on key metrics.

🛠️ Tools & Libraries:
Python (Pandas, NumPy, Seaborn, Scikit-learn, XGBoost, Plotly)
ucimlrepo for dataset access
ydata_profiling for automated EDA
SMOTE & OneSidedSelection for class imbalance

🧪 Models Used:
Logistic Regression
Linear & Quadratic Discriminant Analysis
Random Forest
XGBoost (best performer with ~85% accuracy and 0.93 AUC)

✅ Key Insights:
Education level, age, capital-gain, and hours-per-week are the strongest predictors of income.
XGBoost performed best with 84.5% accuracy and high recall (0.82) for the >$50K class.
Addressed class imbalance through resampling techniques.

✨ Improvements Suggested:
Hyperparameter tuning via GridSearchCV
Fairness audits (gender, race, etc.)
Smarter encoding for high-cardinality categorical features
SHAP/LIME for model explainability
