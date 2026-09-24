# Customer-Churn-Prediction-AI-Dashboard

## 1. Project Overview
This project delivers an end-to-end data analytics and AI solution designed to identify customer attrition patterns, predict at-risk accounts using machine learning, and provide executive stakeholders with an interactive BI dashboard and strategic retention recommendations.

## 2. Dataset
- **Source:** IBM Telco Customer Churn Dataset (Open Tabular Dataset)
- **Observations:** 7,043 customer accounts across 21 demographic, service, and account attributes.

## 3. Technologies Used
- **Python 3.10+** (Core programming language)
- **Pandas & NumPy** (Data cleaning & manipulation)
- **Scikit-Learn** (Random Forest classification & predictive modeling)
- **Plotly & Streamlit** (Interactive executive BI dashboard & visualizations)

## 4. Setup and Run Instructions
1. Clone or download this project folder.
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application and launch the dashboard:
   ```bash
   streamlit run Geetika_CustomerChurnPrediction.py
   ```

## 5. Key Findings & Strategic Recommendations
- **Month-to-month contracts** are the primary driver of attrition, exhibiting a churn rate over 40%.
- Customers with **tenure under 12 months** face the steepest dropout risk.
- **Prescriptive Action:** Offer targeted 1-year contract migration discounts exclusively to the predicted "High Risk" tier to safeguard recurring monthly revenue.
