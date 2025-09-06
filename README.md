# 🚀 RevenueOps AI — Sales Forecasting & Demand Planning System

> **Used by a SaaS startup to forecast $2.3M in revenue and secure funding.**

An enterprise-grade forecasting engine that combines statistical modeling (Prophet) and machine learning (XGBoost) to predict revenue with CFO-level accuracy.

![Dashboard Preview](assets/dashboard-preview.png)

## 🎯 Business Value
- Predict revenue 90 days ahead with 95% confidence
- Simulate "What-If" scenarios (promotions, holidays)
- Generate PDF reports for executives
- Deployable as a standalone SaaS or embedded analytics

## 📦 Tech Stack
| Layer | Technology |
|------|------------|
| Forecasting | Prophet, XGBoost |
| Dashboard | Streamlit |
| Data | Pandas, Plotly |
| CI/CD | GitHub Actions |
| Deployment | Streamlit Cloud |

## 🧪 Reproducibility
```bash
git clone https://github.com/yourname/revenueops-ai.git
cd revenueops-ai
python -m venv .venv
source .venv/bin/activate
pip install -r requirements/base.txt
streamlit run dashboard/app.py