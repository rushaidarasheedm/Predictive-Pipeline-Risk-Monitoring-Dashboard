# Predictive-Pipeline-Risk-Monitoring and-Dashboard

## Project Overview
This project delivers a **predictive analytics solution for pipeline monitoring and maintenance planning**, designed to optimize operations and reduce downtime for onshore oil field pipelines. The dashboard provides **risk assessment, maintenance recommendations, and estimated maintenance costs** using both Python and Power BI.

---

## Business Relevance
- Enables real-time monitoring of **high-risk pipelines**.  
- Supports **predictive maintenance** to prevent failures and reduce costs.  
- Provides actionable KPIs for executives:  
  - Total Pipelines  
  - High-Risk Pipelines (risk_score > 0.8)  
  - Average Risk Score  
  - Estimated Maintenance Costs  

---

## Dataset
- **Source:** Publicly available pipeline dataset  
- **Key Columns:** `Pipe_Size_mm`, `Thickness_mm`, `Time_Years`, `Condition`, `Material`, `Grade`  
    
---

## Technical Workflow
1. **Data Cleaning & Preprocessing**: Handling missing values, encoding categorical variables, and removing duplicates using Python (Pandas, NumPy).  
2. **Predictive Modeling**: Applied **Random Forest Classifier** to predict pipeline conditions and calculate **risk scores**.  
3. **Maintenance Planning**: Generated maintenance actions (`Immediate Maintenance`, `Schedule Maintenance`, `Monitor`) and estimated costs.  
4. **Power BI Dashboard**: Visualized pipeline metrics, risk distribution, and maintenance recommendations through interactive cards, scatter plots, and slicers.  
5. **Export**: Cleaned and processed CSV ready for Power BI: `/powerbi/pipeline_risk_dashboard_final.csv`  

---

## Tools & Technologies
- **Python:** Pandas, NumPy, Seaborn, Scikit-learn  
- **Visualization:** Power BI  
- **Machine Learning:** Random Forest Classifier  
- **Version Control:** Git & GitHub  

---
Outcome

Successfully predicted high-risk pipelines and associated maintenance actions.

Enabled data-driven decision-making for pipeline operations, improving operational efficiency and cost management.

