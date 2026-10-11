## Data science portfolio: I build decision systems, not just models.

Four end-to-end projects spanning fraud detection, customer retention, 
lifetime value, and supply chain operations, each grounded in a business 
problem, framed around a real decision, and shipped with a live app.

Every project follows the same methodology: business framing first, 
cost- and value-aware decisioning, explainability built in, and a 
deployed interface for the people who'd actually use it.

## Projects

| Project | What it does | Stack |
|---------|--------------|-------|
| [**Fraud Detection Decision System**](https://github.com/dave-sm/fraud-detection-decision-system) | End-to-end fraud pipeline with cost-based threshold optimization, SHAP explainability, and a real-time Streamlit decision app. Reduced expected loss **12.6%** over baseline. | Python · Scikit-learn · SHAP · Streamlit · Power BI |
| [**Customer Churn Risk Scoring**](https://github.com/dave-sm/customer-churn-risk-scoring) | Churn framed as a prioritization problem - risk × value scoring, retention economics, and a 7-page Streamlit strategy simulator. Top 30% outreach captures **75.7%** of churners. | Python · Scikit-learn · SHAP · Streamlit · Power BI |
| [**Customer Lifetime Value Analytics**](https://github.com/dave-sm/customer-lifetime-value-analytics) | Dual CLV modeling (probabilistic BG/NBD + Gamma-Gamma, and ML regression) with RFM/K-Means segmentation and a targeting uplift simulator. Top 1% captures **33×** random lift. | Python · lifetimes · Scikit-learn · Streamlit · Power BI |
| [**DataCo Supply Chain Analytics**](https://github.com/dave-sm/dataco-supply-chain-analytics) | SCOR-aligned analytics on 180K transactions - demand forecasting, late-delivery risk scoring, and a leakage audit. Deployed risk scorer with calibrated probabilities (ROC-AUC **0.771**). | Python · LightGBM · SHAP · Streamlit · Power BI |

Each project has its own repo with full methodology, findings, and reproduction steps.

## Skills

**Modeling**  
Logistic Regression · Random Forest · LightGBM · BG/NBD · Gamma-Gamma · K-Means.

**ML practice**  
Imbalanced classification · Cost-sensitive decisioning · Calibration · 
Temporal validation & leakage prevention · Ranking metrics (PR-AUC, Recall @ Top-K%).

**Explainability**  
SHAP (global + local) · Coefficient interpretation · Driver contributions.

**Data & infrastructure**  
SQL · Feature engineering · Medallion architecture (raw/silver/gold) · 
Parquet pipelines · Star schema dimensional modeling.

**Deployment & BI**  
Streamlit · joblib · Power BI (DAX, star schema, dashboards) · Kaggle.

**Business framing**  
KPI design · Cost-based thresholds · ROI simulation · Uplift analysis · 
Sensitivity analysis · Financial leakage attribution.

## How I work

Across all four projects, the same five principles show up:

1. **Business problem first.** Every model is tied to a decision someone actually makes.
2. **Cost- and value-aware.** Thresholds are optimized against financial impact, not defaulted to 0.5.
3. **Explainability built in.** SHAP and coefficient analysis are part of the pipeline.
4. **Leakage discipline.** Temporal splits, feature-cutoff enforcement, and explicit audits.
5. **Shipped pipelines.** Every project has a deployed app and a BI handoff.

---

## Connect

**Email:** davesmbalo@gmail.com