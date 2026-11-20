# Ames Housing SalePrice Regression

Comprehensive residential property valuation model predicting Ames housing sale prices from structural and neighborhood attributes.

## Project Structure

```text
10_Ames_Housing_SalePrice_Regression/
├── ames_housing_saleprice_regression_data.csv
├── ames_housing_saleprice_regression_pipeline.ipynb
├── app.py
├── best_model.pkl
├── model_metadata.json
├── requirements.txt
└── README.md
```

## Dataset & Features

- **Dataset File:** `ames_housing_saleprice_regression_data.csv`
- **Task Type:** `Regression`
- **Target Variable:** `SalePrice`
- **Numerical Features (7):** `OverallQual, GrLivArea, GarageCars, TotalBsmtSF, YearBuilt, FullBath, LotArea`
- **Categorical Features (2):** `Neighborhood, KitchenQual`

## Model Evaluation Summary

- **Selected Best Model:** `Ridge`

| Metric | Score |
| :--- | :--- |
| `r2` | `0.9441` |
| `mae` | `27061.4` |
| `rmse` | `33722.03` |

## Quickstart & Deployment

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
