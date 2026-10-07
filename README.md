# swedish-electricity-price-forecasting
Forecasting Swedish electricity prices using time-series analysis and machine learning.
## Model Results

| Model | MAE (EUR/MWh) | RMSE (EUR/MWh) |
|---|---:|---:|
| Linear Regression | 7.32 | 11.32 |
| Gradient Boosting | 7.51 | 11.39 |
| Random Forest | 8.65 | 13.04 |
| Previous-day Baseline | 28.47 | 40.34 |

Linear Regression achieved the lowest MAE and RMSE on the chronological test set.

The result shows that, for the current feature set, the simpler linear model outperformed the more complex tree-based models.