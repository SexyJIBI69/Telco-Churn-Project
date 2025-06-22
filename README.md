# Telco-Churn-Project
A project where IBM’s 7 K-row Telco-Customer dataset is cleaned in Python and modeled with logistic regression, and exports churn probabilities, and feeds an interactive Power BI dashboard that lets managers explore churn risk by contract length, internet service, and monthly charges.

# 📞 Telco Customer Churn – Mini Project

**Goal:** Predict which telecom customers will likely churn and create a business-ready Power BI dashboard.

| Item | Details |
|------|---------|
| **Dataset** | IBM Telco Customer Churn – 7,043 rows × 21 columns |
| **Source** | Public IBM sample (_raw CSV pulled directly in Notebook_) |
| **Target** | `Churn` (`Yes` = 1, `No` = 0) |
| **Model** | Logistic Regression (L2, `max_iter=1000`) |
| **Performance** | **Accuracy 91 %** • **F1 60 %** • **ROC AUC 0.82** |
| **Artifacts** | `telco_churn_clean.csv` (predictions) → Power BI dashboard |

---

## Key Insights

* **Month-to-Month contracts** churn 4× more than 2-year contracts.  
* **Fiber-optic** users show the highest churn risk (≈ 44 %).  
* Higher **Monthly Charges (> $70)** correlate with churn probabilities > 60 %.

These insights feed directly into the **Power BI “Executive Summary” dashboard** for business users.
