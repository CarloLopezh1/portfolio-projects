# Project 5 – T20 Cricket Player Index: Modeling Player Impact

**Tools Used:** Python (Jupyter Notebook), pandas, scikit-learn, XGBoost, SHAP

This project builds a custom player performance index for T20 cricket using data from five merged datasets. Players were clustered by role (batters, bowlers, wicketkeepers), and separate pipelines were used to model their impact on match outcomes. The project combines unsupervised and supervised learning with interpretable visuals to support data-informed strategy for player selection, team balance, and recruitment.

---

## Project Highlights

- **Role-Based Clustering**: Grouped players into performance-based clusters using K-Means.
- **Predictive Modeling**: Built XGBoost classifiers to predict match outcomes based on player features and clusters.
- **Model Interpretability with SHAP**: Used SHAP values to explain key factors driving match wins for each role type.
- **Strategic Insights**: Identified player types most associated with high-impact performances across batting and bowling roles.

---

## Tools & Skills

- Python (pandas, scikit-learn, XGBoost, SHAP)
- Feature engineering and clustering
- Supervised machine learning
- Role-based modeling
- Model interpretation and visualization
- Data storytelling for sports strategy

---

## Visual Insights

### Player Clusters by Role
Grouped batters, bowlers, and keepers by performance metrics using K-Means.

![Player Clusters](./images/player-clusters.png)

---

### SHAP Summary – Bowler Impact
Explained the most important features in the XGBoost model for predicting match outcomes.

![SHAP Summary](./images/shap-summary-bowlers.png)

---

### Cluster Performance – Batters
Analyzed win rates and average runs per cluster to assess batting impact.

![Batter Impact](./images/batter-cluster-impact.png)

---

### Strategic Summary
Key recommendations for team composition and recruitment based on role impact.

![Insights Summary](./images/key-insights-summary.png)

---

## 📁 Files Included

- `T20 Cricket Report.pdf`: Final report with visuals and strategic takeaways

---

## Reflection

This project deepened my understanding of how machine learning can drive decisions in sports management. I explored both performance profiling and outcome prediction, and practiced explaining technical models through visuals that support real-world decisions in team building and strategy.

