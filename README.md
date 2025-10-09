# Will the Customer Accept the Coupon?


## Baseline Model (Logistic Regression)
We added a simple baseline model using one-hot encoded categorical variables and median-imputed numerics.

**Results (hold-out test set):**
- **AUC:** 0.732
- **F1 score:** 0.736

You can reproduce the model in `notebooks/coupon_acceptance_full.ipynb`. The ROC curve is saved at `figures/roc_curve.png`.
