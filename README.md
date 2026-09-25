# Modeling and Optimization of a Hydroprocessing Unit

This project uses operating data and machine learning to predict product yields and explore improved operating conditions for a hydroprocessing unit.

## Notebook

`hydroprocessing_modeling_optimization.ipynb`

The notebook models distillate, naphtha, and C1–C4 yields across two operating modes. It includes:

- Data cleaning, missing-data imputation, and outlier removal.
- Comparison of Decision Tree, Random Forest, SVR, XGBoost, LightGBM, CatBoost, and deep neural network models.
- Model evaluation using MAE, RMSE, and R².
- SHAP and LIME for interpreting model predictions.
- Multi-objective optimization using CatBoost models and NSGA-II to improve distillate yield under low- and high-yield conditions.

## Data and Dependencies

The notebook requires the input files `Cycle 1.csv` through `Cycle 6.csv`.

Main Python libraries: pandas, NumPy, SciPy, Matplotlib, seaborn, scikit-learn, XGBoost, LightGBM, CatBoost, TensorFlow, SHAP, LIME, and pymoo.

## Author

Arian Rezaei
