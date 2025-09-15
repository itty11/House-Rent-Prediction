# House-Rent-Prediction
This repository contains a Machine Learning project to predict house/apartment rents based on multiple features like city, BHK, size, furnishing status, etc. The goal is to build regression models and evaluate their performance to accurately estimate rental prices.


# Files

House_Rent_Dataset.csv – Dataset used for training & testing.

house_rent_prediction.ipynb – Jupyter Notebook with full code.

# Dataset Glossary

| Column                | Description                                        |
| --------------------- | -------------------------------------------------- |
| **BHK**               | Number of Bedrooms, Hall, Kitchen                  |
| **Rent**              | Rent of the property                               |
| **Size**              | Size in square feet                                |
| **Floor**             | Floor number and total floors (e.g., `3 out of 5`) |
| **Area Type**         | Super Area / Carpet Area / Build Area              |
| **Area Locality**     | Locality of the property                           |
| **City**              | City name                                          |
| **Furnishing Status** | Furnished / Semi-Furnished / Unfurnished           |
| **Tenant Preferred**  | Preferred tenant type                              |
| **Bathroom**          | Number of bathrooms                                |
| **Point of Contact**  | Contact person                                     |


# Results

| Model             | RMSE     | MAE      | R²   |
| ----------------- | -------- | -------- | ---- |
| Linear Regression | 48944.50 | 23527.27 | 0.40 |
| Random Forest     | 37142.90 | 11401.77 | 0.65 |
| XGBoost           | 34700.60 | 12367.72 | 0.70 |
| LightGBM          | 38323.62 | 13367.63 | 0.63 |

(Values will vary based on preprocessing and train/test split.)

# Future Work

Hyperparameter tuning using GridSearchCV

Deployment as a web app (Streamlit / Flask)

Adding geospatial data for better predictions
