# Telco-Churn-Predictor-PowerBI
End-to-end Telco Customer Churn Analysis using Python (Logistic Regression) + Power BI Dashboard
# Telco Customer Churn Predictor – Python + Power BI

End-to-end project predicting customer churn for a telecom company using machine learning and interactive dashboards.

## Project Overview
- **Dataset**: IBM Telco Customer Churn (~7K records)
- **Objective**: Identify churn drivers, predict at-risk customers, and visualize actionable insights
- **Key Findings**:
  - Month-to-month contracts → ~45% churn rate
  - Fiber optic users → significantly higher risk
  - Lack of OnlineSecurity/TechSupport → major driver
  - Flagged ~22% high-risk customers with **$1.46M** potential annual revenue loss

## Tech Stack
- **Python**: Pandas, NumPy, Seaborn, Scikit-learn (Logistic Regression, AUC 0.85)
- **Power BI**: DAX measures, slicers, drill-through, conditional formatting
- **Tools**: Google Colab, Power BI Desktop

## Files
- `churn_analysis.ipynb`: Full Python code (EDA → modeling → prediction)
- `telco_churn_enriched.csv`: Dataset with churn probability & risk flags
- `Telco_Churn_Dashboard.pbix`: Interactive Power BI file
- `/screenshots/`: Dashboard visuals

## Dashboard Screenshots

### Executive Overview
![Executive Overview] <img width="1340" height="732" alt="Executive Overview" src="https://github.com/user-attachments/assets/6fccda7a-60f1-48c1-bea4-e316c76a151a" />


### Segment Analysis
![Segment Analysis](screenshots/segment-analysis.png)

### High-Risk Customers Table
![High-Risk Table](screenshots/high-risk-table.png)

## How to Run
1. Open `churn_analysis.ipynb` in Google Colab → Run all cells
2. Download enriched CSV
3. Open `.pbix` in Power BI Desktop → Refresh if needed

## Business Recommendations
- Target month-to-month Fiber optic customers with discounts/loyalty offers
- Promote OnlineSecurity & TechSupport bundles to reduce churn

Feel free to connect: [LinkedIn](www.linkedin.com/in/arnav-mehta-43b790230) | [Email](arnavmehta2903@gmail.com)
