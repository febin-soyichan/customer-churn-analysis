# Telecom Customer Churn & Revenue Risk Analysis

## Project Overview
Customer churn is a major challenge in the telecommunications industry. This repository explores a dataset of 7,000+ customer records to identify churn drivers, calculate 12-month revenue at risk, and present strategic retention recommendations using Python and Tableau.

## Tools & Technologies
* **Language:** Python
* **Data Processing & Analysis:** Pandas, NumPy
* **Data Visualization:** Tableau, Matplotlib
* **Environment:** Jupyter Notebook / Google Colab

## Key Milestones & Workflow
1. **Data Transformation & Feature Engineering:** Cleaned telecom customer records in Python (Pandas), addressing missing data and engineering custom groupings for customer tenure, monthly charge quartiles, and revenue metrics.
2. **Financial Risk Analysis:** Estimated 12-month revenue-at-risk indicators to quantify the potential financial impact of lost subscribers.
3. **Pattern Identification:** Analyzed churn variance across contract types (Month-to-month vs. 1/2 Year contracts), payment options, and service features.
4. **Interactive Dashboard:** Designed an interactive Tableau dashboard showcasing high-level KPIs (Total Customers, Churn Rate %, ARPU, Revenue at Risk) alongside segment breakdowns.

## Business Logic & Analysis

### Key Insights (What the data tells us)
* **High Customer Loss (Churn):** **26.5%** of customers are leaving the service, putting **$1.67 Million in revenue at risk** over 12 months.
* **Month-to-Month Contracts are Risky:** Around **42%** of month-to-month customers leave, compared to only 11% on 1-year plans and under 3% on 2-year plans.
* **New Customers Leave First:** Customers in their **first 6 months** and those paying with **Electronic Checks** are the most likely to cancel.

### Underlying Causes (Why this is happening)
* **Easy to Walk Away:** Month-to-month customers have no contract, making it effortless for them to switch to a competitor whenever they get frustrated.
* **Poor Onboarding Experience:** High cancellation rates in the first 6 months mean new users likely face setup confusion or poor early customer service.
* **Payment Hassles:** Electronic check payments require manual action every month, increasing the chance of payment failure or frustration compared to automatic bank payments.

### Recommended Solutions (What to do next)
* **Incentivize Long-Term Contracts:** Offer a discount or free add-on if month-to-month users upgrade to a 1-year or 2-year contract.
* **Improve the First 90 Days:** Reach out to new customers with simple guides and extra customer support during their first 3 to 6 months.
* **Promote Auto-Pay:** Give a small monthly bill discount to users who switch from Electronic Checks to Automatic Bank Transfers.
