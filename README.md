# Workforce Attrition Risk & Financial Impact Analysis

## Project Summary

This project performs a structured workforce analytics study on the IBM HR dataset to quantify employee attrition risk, identify key turnover drivers, and estimate the financial exposure associated with employee churn.

The analysis emphasizes KPI development, relative risk benchmarking, and business impact modeling using Python-based exploratory and statistical techniques.

---

## Business Objective

Employee attrition leads to:

- Increased recruitment and onboarding costs  
- Loss of productivity and institutional knowledge  
- Operational instability  

The objective of this project is to:

- Measure and benchmark attrition risk across employee segments  
- Identify structural drivers of turnover  
- Quantify financial exposure due to attrition  
- Simulate potential cost-reduction interventions  

---

## Dataset

**IBM HR Analytics – Employee Attrition Dataset**

- ~1,470 employee records  
- ~35 features including demographics, job info, compensation, tenure, performance, and satisfaction variables  

---

## Methodology

### 1. Data Preparation
- Cleaned and preprocessed the dataset  
- Converted the attrition variable to a binary format  
- Engineered tenure bands, salary bands, and age groups  
- Handled categorical segmentation for risk profiling  

### 2. KPI & Risk Modeling
- Calculated overall attrition rate  
- Computed attrition rates by department, tenure, and other segments  
- Developed relative risk scores (segment attrition ÷ overall attrition)  
- Calculated overtime risk multipliers  
- Visualized attrition behavior by key business segments  

### 3. Financial Impact Estimation
- Estimated replacement and churn costs using salary-based assumptions  
- Calculated annual attrition cost exposure  
- Modeled potential cost reduction from targeted interventions  

### 4. Visualization & Reporting
- Built an interactive executive dashboard using Plotly  
- Created KPI summaries and trend visualizations  
- Designed charts for relative risk and attrition segmentation  

---

## Key Analytical Findings

- Employees working overtime show ~2× higher attrition risk compared to baseline  
- A tenure “cliff” effect is observed within the first 2 years of service  
- Department-level benchmarking identifies areas with elevated turnover  
- Lower job satisfaction correlates with higher attrition probability  
- Attrition carries significant financial exposure under replacement cost modeling  

---

## Business Value

This analysis demonstrates how workforce data can be transformed into:

- Quantified attrition risk indicators  
- Financial impact estimates  
- Data-driven HR strategy recommendations  
- Structured decision-support insights  

---

## Future Scope

- Multivariate risk interaction analysis  
- Predictive attrition modeling using machine learning  
- Automated HR decision-support dashboard  

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly

## 📷 Visual Summary

<img src="outputs/HR Attrition EDA Dashboard 1.png" width="600"/>
<img src="outputs/HR Attrition EDA Dashboard 2.png" width="600"/>
<img src="outputs/HR Attrition EDA Output 1.png" width="600"/>
<img src="outputs/HR Attrition EDA Output 2.png" width="600"/>
