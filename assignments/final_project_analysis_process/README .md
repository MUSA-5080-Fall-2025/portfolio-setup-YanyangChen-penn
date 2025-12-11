C. Model Validation and Performance

This project underwent rigorous out-of-sample validation through time series segmentation (training set < 2023, test set ≥ 2023).

| Error Metric | In-Sample | Out-of-Sample |
| :-- - | :--- | :--- |
| **MAE (Mean Absolute Error)** | $0.1481$ | $0.2173$ |
| **RMSE (Root Mean Square Error)** | $0.1982$ | $0.2464$ |

* **Evaluation:** Out-of-sample error is slightly higher than in-sample, but the difference remains within a reasonable range. This indicates the model possesses good generalization capabilities in predicting eviction fluctuations for 2023 and beyond, avoiding overfitting.
* **Residual Distribution:** Residual plots confirm the similarity in error distributions between in-sample and out-of-sample data, supporting the model's robustness.