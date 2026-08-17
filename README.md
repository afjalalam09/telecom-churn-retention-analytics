# Telecom Customer Churn & Retention Analytics 📊

## 📌 Project Overview
Customer retention is a critical key performance indicator in the telecommunications industry. This end-to-end Data Analytics project analyzes telecom customer records to identify the core drivers of customer churn, measure financial impact, and provide actionable business recommendations to minimize revenue loss.

---

## 🛠️ Tech Stack & Workflow
* **Tool:** Microsoft Power BI Desktop
* **ETL (Extract, Transform, Load):** Power Query Editor used for data ingestion, cleaning missing values, and formatting data types.
* **Data Modeling & DAX:** Created a custom calculated measure table and dynamic business metrics using advanced Data Analysis Expressions (DAX).
* **Data Visualization:** Designed an interactive, executive-ready dark-themed dashboard focused on key risk indicators.

---

## 📐 Core DAX Measures Implemented
* **Total Customers:** `COUNT(Customer_Churn_Data[customerID])` to establish the active baseline.
* **Churned Customers:** `CALCULATE(COUNT(...), Churn = "Yes")` to track total service cancellations.
* **Retained Customers:** `CALCULATE(COUNT(...), Churn = "No")` to track active, loyal users.
* **Churn Rate %:** `DIVIDE([Churned Customers], [Total Customers])` for dynamic percentage calculation.
* **Average Monthly Charges:** Segmented across Churned vs. Retained cohorts to evaluate financial impact and cost sensitivity.

---

## 💡 Key Business Insights
* **High Overall Churn:** The company exhibits a concerning overall churn rate of **26.54%** (1,869 out of 7,043 customers).
* **Contract Vulnerability:** Customers on **Month-to-Month contracts** account for the vast majority of drop-offs (1,655 users), whereas 1-year and 2-year contracts show strong retention.
* **Early-Stage Drop-off:** The first 6 months of customer tenure represent the highest risk period, peaking at a **52.94%** churn rate in the 0–6 month band.
* **Pricing Correlation:** Churned customers carry a higher average monthly bill ($74) compared to retained customers ($61), signaling clear pricing friction.

---

## 🚀 Strategic Recommendations
* **Incentivize Long-Term Commitments:** Provide strategic discounts or loyalty perks to convert month-to-month users into 1-Year or 2-Year contracts.
* **Enhance Early Onboarding:** Introduce proactive customer support and engagement touchpoints during the first 6 months to reduce the 52% early-drop-off rate.
* **Promote Add-on Services:** Encourage service bundling (such as 'Online Security' and 'Tech Support') to increase customer engagement and reduce abandonment.

---

## 📂 Repository File Structure
* `Telco_Customer_Churn_Dashboard.pbix` - The complete, interactive Power BI report file.
* `Raw_Telco_Customer_Data.csv` - The original uncleaned source dataset demonstrating ETL readiness.
* `Final_Executive_Dashboard_View.png` - Visual preview snapshot of the dashboard UI.
