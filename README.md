# Customer Analytics Case Studies

These cases are designed to give hands-on experience with real-world data, predictive modeling, and data-driven decision making. The notebooks cover a variety of modeling techniques and business problems, including several examples of A/B testing and experimental design.

## Overview of Cases

**A/B Testing & Experimental Design:**
- Several cases (especially Creative Gaming: Uplift Modeling and Propensity-to-Buy) use randomized control and treatment groups to measure the impact of marketing interventions. These are classic examples of A/B testing in analytics.

---

### [1. Tuango: Targeting Mobile App Messages](tuango.ipynb)
Optimizes which customers should receive mobile app messages to maximize response rates and order sizes. Uses logistic regression (for predicting likelihood to respond/buy) and linear regression (for estimating expected order size). Includes buyer prediction, order size modeling, and profitability analysis.

### [2. TZ Gaming: Optimal Targeting of Mobile Ads](tz-gaming.ipynb)
Improves ad targeting to maximize clicks and marketing ROI. Uses logistic regression (for click probability prediction), decile analysis (for segmenting and ranking users by likelihood to click), confusion matrix (for evaluating targeting accuracy), and profit/ROME calculations (for financial impact assessment). Includes model comparison and campaign simulation.

### [3. Intuit QuickBooks Upgrade](intuit.ipynb)
Identifies customers most likely to upgrade to a new product version. Uses logistic regression (for upgrade probability), and neural networks (for uncovering non-linear upgrade patterns). Focuses on model evaluation, targeting strategies, and profit optimization.

### [4. Creative Gaming: Propensity-to-Buy](cg-prop.ipynb)
Predicts which customers are most likely to make a purchase. Uses logistic regression (for probability estimation), random forest (for feature importance and non-linear effects), and neural networks (for complex pattern recognition). Includes model comparison (AUC, gains), profit analysis, and experimental design elements. Demonstrates A/B testing by comparing control and treatment groups to evaluate marketing impact.

### [5. Creative Gaming: Uplift Modeling](cg-uplift.ipynb)
Measures the true effect of marketing by estimating the incremental impact (uplift) of ads on customer conversions. Uses uplift models (to separate treatment effect from baseline), random forest and XGBoost (for flexible, high-performance uplift estimation), and neural networks (for capturing complex interactions). Demonstrates A/B testing logic for treatment effect estimation.

### [6. Pentathlon: Next Product to Buy](pentathlon_nptb.ipynb)
Forecasts which product a customer is most likely to purchase next. Uses logistic regression (for purchase likelihood), random forest and XGBoost (for ranking product features and handling complex data), neural networks (for deep feature interactions), and linear regression (for predicting order size or value). Includes advanced modeling, feature engineering, and profit analysis.

### [7. S-Mobile: Customer Churn](s-mobile.ipynb)
Predicts which customers are at risk of leaving (churn) and uncovers the main reasons for churn. Uses logistic regression (for churn probability and driver analysis) and XGBoost (for ranking churn factors and improving prediction accuracy). Includes actionable insights and customer lifetime value calculations.

### [8. FiTech: Customer Adoption and Value](fitech.ipynb)
Predicts key outcomes such as product adoption, usage frequency, or customer value. Applies logistic regression (for probability estimation), random forest and XGBoost (for feature ranking and handling complex data), and neural networks (for uncovering deep patterns). Includes model evaluation, feature engineering, and actionable insights for marketing or product strategy.


