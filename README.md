# Machine Learning for Education and Economy Data

Tema 1 project for Inteligență Artificială (IA). The notebook explores an education and economy dataset, prepares mixed numerical and categorical features, and compares classification and regression models.

## Notebook workflow

1. **Explore the data:** inspect missing values, column types and ranges, class balance, and feature correlations.
2. **Prepare features:** impute missing values, examine extreme values and redundant columns, encode categorical attributes, and normalize or standardize numerical values where needed.
3. **Train and compare classifiers:** experiment with decision trees, random forests, and histogram-based gradient boosting, using validation metrics to compare configurations.
4. **Evaluate regression models:** compare linear and regularized regression approaches, including CatBoost regression experiments where available in the notebook.
5. **Prepare Kaggle predictions:** the final section applies the selected workflow to the competition evaluation data.

## Files

- `education_economy_ml.ipynb` — analysis, preprocessing, experiments, and evaluation.
- `CC_education_economy_train.csv`, `CC_education_economy_test.csv` — included competition data used by the notebook.
- `Raport_Tema1_IA.pdf` — written project report.

Open the notebook in Jupyter. It uses Python with pandas, NumPy, scikit-learn, Matplotlib, and Seaborn; some model experiments may also require CatBoost. Private test data and generated training logs are not included.
