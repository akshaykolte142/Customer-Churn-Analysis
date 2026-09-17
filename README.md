# Customer-Churn-Analysis
PlayWave Customer Churn Analysis is an end-to-end data analytics project focused on understanding customer churn, identifying high-risk customer segments, and quantifying revenue at risk.

Using a synthetic dataset of 221 subscribers, the project combines SQL-based data extraction with Python and Pandas for data cleaning, feature engineering, exploratory analysis, customer segmentation, statistical correlation analysis, and visualization. The analysis examines churn across subscription plans, contract types, geographic segments, acquisition channels, customer complaints, cancellation reasons, churn risk, and customer lifetime value (CLTV).

The analysis found a 35.29% churn rate, with $1,715.22 in monthly recurring revenue associated with churned customers. Standard-plan customers recorded the highest plan-level churn rate at 40.24%, while 30.8% of customers were classified as High Risk. The analysis also found that "Forgot to cancel trial" was the most frequently reported cancellation reason, followed by price and streaming-quality concerns.

Rather than focusing only on churn percentages, the project translates analytical findings into revenue-linked retention opportunities, demonstrating how SQL and Python can be used to support data-driven business decisions.
## Key Findings

- **35.29% customer churn rate** — 78 out of 221 analyzed customers had churned.
- **$1,715.22 monthly revenue associated with churned customers**, highlighting the financial impact of customer attrition.
- **Standard plan had the highest churn rate at 40.24%**, followed by Basic at 36.25% and Premium at 27.12%.
- **Standard plan had the highest high-risk revenue exposure at $685.73.**
- **30.8% of customers were classified as High Risk**, creating a defined segment for retention analysis.
- **"Forgot to cancel trial" was the most common cancellation reason**, with 18 cases, followed by "Too expensive" with 17 cases.
- **Escalations showed a weak correlation with churn (r = 0.08)**, suggesting that support escalation was not strongly associated with customer cancellation in this dataset.
- **Karnataka (50.00%) and Delhi (41.86%) recorded the highest state-level churn rates** in the analyzed data.
- **Organic acquisition had the lowest churn rate (30.49%)** compared with Referral (38.81%) and Paid (37.50%).
