# Azure Cost Management, Budgets & Alerts Lab

## 🎯 Objective
Configured cloud governance financial controls by establishing a subscription-level budget, defining automated spending threshold alerts, and verifying budget deployment metrics to monitor cloud expenditure.

## 🛠️ Tech Stack & Concepts
* **Cloud Platform:** Microsoft Azure
* **Cost Management:** Cost Analysis, Subscription Budgets ($50.00 USD Monthly)
* **Governance & Alerts:** Actual Cost Threshold Triggers (50% / $25.00), Automated Email Notifications

---

## 📋 Implementation Walkthrough & Screenshots

### 1. Budget Creation & Financial Parameters
Configured a monthly recurring budget (`workshopbudget`) scoped at the subscription level with a $50.00 USD threshold, tracking active spend over a designated lifecycle period.
* **Configuring Budget Details & Threshold Amount:**
![Create Budget Details](./screenshots/create-budget.jpg)

### 2. Alert Conditions & Notification Setup
Established automated alerting rules tied to actual spend conditions (triggering at 50% / $25.00 of the total budget) and designated target email recipients for proactive cost monitoring.
* **Setting Alert Conditions & Email Recipients:**
![Set Budget Alerts](./screenshots/set-alerts.jpg)

### 3. Deployment Verification & Monitoring Summary
Verified the completed budget deployment within the Azure Portal, reviewing summary parameters, expiration timelines, and active alert criteria.
* **Budget Summary & Deployment Overview:**
![Budget Deployed Successfully](./screenshots/budget-deployed.jpg)

---

## 🚀 Key Takeaways
* Successfully implemented cost-control boundaries and budget tracking mechanisms in Azure to prevent unexpected resource expenditures.
* Configured automated alert thresholds to ensure proactive notification before reaching financial limits.