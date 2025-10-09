# Will the Customer Accept the Coupon?

**Exploratory Data Analysis (EDA) in Python (Pandas + Matplotlib)**  
Author: Felipe E. Ulloa  
Date: 2025-10-09

This project analyzes a dataset from the UCI Machine Learning Repository (survey conducted via Amazon Mechanical Turk) to answer the question:  
**Will a customer accept a driving coupon?** (`Y=1` for “immediately” or “later before expiration”; `Y=0` for “no”).

## Repository Structure
```
coupon_project_en/
├── README.md
├── notebooks/
│   └── coupon_acceptance.ipynb
├── data/
│   └── coupons.csv
├── figures/
│   └── acceptance_by_coupon.png
├── LICENSE
└── .gitignore
```

## Key Findings
- **Overall acceptance rate:** 56.8%
- **Most accepted coupon:** Carry out & Take away (73.5%)

Acceptance rates differ significantly depending on **coupon type, time of day, weather, companions, and destination**.

## Actionable Recommendations
1. **Prioritize top-performing coupon types** in marketing campaigns.
2. **Target promotions during high-acceptance periods** (e.g., specific times or weather conditions).
3. **Contextual segmentation**: tailor messages based on whether the driver is alone or with friends/family, and their destination.
4. **Next steps**: build a baseline logistic regression model to quantify feature importance (coupon, time, passenger, weather, income, age, etc.).

## How to Run Locally
1. Install **Anaconda (Python 3.11+)** and open **Jupyter Notebook**.
2. Clone or download this repository.
3. Run `notebooks/coupon_acceptance.ipynb` to reproduce the analysis.

## License
MIT License © 2025
