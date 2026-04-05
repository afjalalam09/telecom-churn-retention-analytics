# Telecom Customer Churn & Retention Analytics 📊

## 📌 Project Overview
The telecommunication industry faces intense competition, making customer retention a critical priority. This project analyzes telecom customer behavior to identify the key drivers of churn and provides data-driven recommendations to improve retention rates.

## 🛠️ Tech Stack & Tools
* **Visualization:** Power BI
* **Data Transformation:** Power Query (ETL)
* **Analytical Calculations:** Advanced DAX (Data Analysis Expressions)
* **Industry Focus:** Telecommunications & Business Intelligence

## 💡 Key Business Insights
* **Churn Rate:** The baseline churn rate is **26.54%**, with 1,869 customers leaving the service.
* **Contract Risk:** Customers on **Month-to-Month contracts** have the highest churn density, contributing to over 1,600 churned cases.
* **Pricing Factor:** Churned customers had a higher average monthly charge (**$74**) compared to retained customers (**$61**), indicating price sensitivity.
* **Tenure Impact:** The most critical risk period is the first **0-6 months**, where over 50% of the total churn occurs.

## 📊 Dashboard Preview
![Dashboard Screenshot](dashboard_screenshot.jpg)

*(Note: The initial dataset `telco_churn_unclean.csv` was raw. All data cleaning, formatting, and ETL processes were handled directly inside Power BI using Power Query before building the visualizations.)*

## 🚀 Actionable Recommendations
1. **Contract Incentives:** Target Month-to-Month customers with loyalty discounts to upgrade them to 1-Year or 2-Year contracts.
2. **Early Intervention:** Implement a proactive "Onboarding Retention Program" for new customers during their high-risk first 6 months.
3. **Value-Added Services:** Bundle 'Online Security' and 'Online Backup' services for high-paying customers, as data shows these features increase customer stickiness.

## 📁 Repository Structure
* `telco_churn_unclean.csv`: The raw dataset used for analysis.
* `Telecom_Churn_Analysis.pbix`: The complete Power BI dashboard file (includes Power Query steps and DAX measures).
* `dashboard_screenshot.jpg`: High-resolution snapshot of the final dashboard.
* `README.md`: Project documentation and insights.
