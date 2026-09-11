# Employee Retention Strategy using Machine Learning

## 📌 Project Overview

High employee turnover is a critical cost driver in the IT consulting sector. Replacing a skilled consultant costs roughly 6-9 months of their salary. This project moves away from reactive HR measures to a **proactive, AI-driven intervention strategy**.

By analyzing HR data from "Company I" (1,470 employees), this project utilizes **LightGBM** to predict attrition risk and simulates a targeted "Premium Retention Package" to maximize profitability.

## 🎯 Key Objectives

1.  **Analyze** historical employee data to identify key drivers of attrition.
2.  **Predict** "High-Risk" employees using Machine Learning.
3.  **Simulate** a financial intervention to calculate potential Return on Investment (ROI).

## 🛠️ Methodology & Tech Stack

  * **Data Preprocessing:** Handling categorical variables (One-Hot Encoding), dropping redundant features, and correlation analysis.
  * **Modeling:** Gradient Boosting Framework (**LightGBM**) for high interpretability and speed.
  * **Evaluation:** ROC-AUC Score and Classification Accuracy.
  * **Libraries:** `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `LightGBM`, `Scikit-learn`.

## 📊 Key Insights & Performance

The model achieved an **Accuracy of 88.1%** and a **ROC-AUC score of 0.85**, demonstrating outstanding predictive power.

### Top Drivers of Attrition:

1.  **Monthly Income:** The strongest indicator; financial dissatisfaction is the primary trigger.
2.  **OverTime:** A key indicator of burnout risk.
3.  **Incentives & Stock Options:** Critical levers for retention.

## 💰 Business Impact Simulation

We simulated a "Premium Retention Package" ($5,000 boost in incentives/stock) offered *only* to employees identified as high-risk by the AI.

  * **Scenario:** 28 employees identified as high-risk.
  * **Intervention Outcome:** The model predicted 12 of them (42.9%) would stay after the incentive.
  * **Financial Projection:**
      * **Savings:** $360,000 (Avoided hiring costs).
      * **Cost of Intervention:** $140,000.
      * **Net Profit:** **$220,000**.

## 📂 Repository Structure

  * `project.ipynb`: The main source code containing EDA, Modeling, and ROI simulation.
  * `proposal_report.pdf`: Detailed presentation of the business strategy and findings.
  * `data.csv`: The HR Analytics dataset.

## 📜 References

  * IBM HR Analytics Employee Attrition & Performance Dataset
