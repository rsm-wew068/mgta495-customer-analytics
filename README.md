# Customer Analytics Case Studies

This repository contains a collection of advanced business analytics case studies, each designed to provide hands-on experience with real-world data, predictive modeling, and data-driven decision making. The cases are implemented as Jupyter notebooks and cover a range of modeling techniques and business problems.

## Case Summaries

### 1. Creative Gaming: Propensity-to-Buy (`cg-prop.ipynb`)
- **Goal:** Predict customer propensity to buy using various machine learning models.
- **Models:** Logistic Regression, Random Forest, Neural Network (MLPClassifier).
- **Highlights:** Model comparison using AUC, gains, and profit analysis.

### 2. Creative Gaming: Uplift Modeling (`cg-uplift.ipynb`, `cg-uplift answer.ipynb`)
- **Goal:** Estimate the incremental impact of marketing using uplift models.
- **Models:** Uplift models, Random Forest, XGBoost, Neural Network.
- **Highlights:** Comparison of uplift vs. propensity models, treatment effect estimation.

### 3. Intuit QuickBooks Upgrade (`intuit.ipynb`, `intuit_ct.ipynb`)
- **Goal:** Predict which customers are likely to upgrade to a new product version.
- **Models:** Logistic Regression, Neural Network.
- **Highlights:** Model evaluation for targeting and profit optimization.

### 4. Pentathlon: Next Product to Buy (`pentathlon_nptb.ipynb`)
- **Goal:** Predict the next product a customer will buy.
- **Models:** Logistic Regression, Random Forest, Neural Network, XGBoost, Linear Regression.
- **Highlights:** Advanced modeling, feature engineering, and profit analysis.

### 5. S-Mobile: Customer Churn (`s-mobile.ipynb`, `s-mobile answer.ipynb`)
- **Goal:** Predict customer churn and identify key churn drivers.
- **Models:** Logistic Regression, XGBoost.
- **Highlights:** Feature importance, impact analysis, and retention strategy.

### 6. Tuango: Targeting Mobile App Messages (`tuango.ipynb`)
- **Goal:** Target mobile app messages to maximize customer response and order size.
- **Models:** Logistic Regression, Linear Regression.
- **Highlights:** Buyer prediction and order size modeling.

### 7. TZ Gaming: Optimal Targeting of Mobile Ads (`tz-gaming.ipynb`, `tz-gaming copy.ipynb`)
- **Goal:** Optimize ad targeting to maximize clicks and marketing ROI.
- **Models:** Logistic Regression, model evaluation (decile analysis, confusion matrix, profit/ROME).
- **Highlights:** Model comparison, regularization discussion, and campaign simulation.

## Getting Started

1. **Environment:**
   - All notebooks are designed to run in a Python environment with standard data science libraries (pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost, etc.) and the `pyrsm` package.
   - Some notebooks require data files in a `data/` subfolder.

2. **Usage:**
   - Open any notebook in JupyterLab or VS Code.
   - Follow the instructions and run cells sequentially.
   - Review markdown cells for case context, business questions, and interpretation guidance.

3. **Collaboration:**
   - Many cases are designed for group work and include workflow tips for using GitHub.
   - Ensure reproducibility by not installing extra packages and keeping code self-contained.

## License
These case studies are for educational use only. Please do not share solutions outside your course or cohort.

---

For questions or support, contact your course instructor or teaching assistant.
