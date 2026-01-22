# Bacterial Growth Regression using Machine Learning

This project explores machine learning regression models to predict bacterial growth parameters (`a`, `μ`, `τ`, `a₀`) from experimental conditions such as CO₂ availability, light and sucrose efficiency.

## What this project demonstrates
- End-to-end machine learning workflow
- Target-specific preprocessing
- Model comparison and hyperparameter tuning
- Rigorous evaluation using RMSE and R²
- Interpretation of results and limitations

## Models used
- Ridge and Polynomial Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Key results
- Ensemble models achieved R² > 0.97 for multiple targets
- Target-specific tuning significantly improved performance
- Simpler targets required lower model complexity

See `bacterial_growth_regression.ipynb` for full analysis.
