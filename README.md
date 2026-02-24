Workforce Attrition Risk & Financial Impact Analysis
Project Summary

This project performs a structured workforce analytics study on the IBM HR dataset to quantify employee attrition risk, identify key turnover drivers, and estimate the financial exposure associated with employee churn.

The analysis emphasizes KPI development, relative risk benchmarking, and business impact modeling using Python-based exploratory and statistical techniques.

Business Objective

Employee attrition leads to:

Increased recruitment and onboarding costs

Loss of productivity and institutional knowledge

Operational instability

The objective of this project is to:

Measure and benchmark attrition risk across employee segments

Identify structural drivers of turnover

Quantify financial exposure due to attrition

Simulate potential cost-reduction interventions

Dataset

IBM HR Analytics – Employee Attrition Dataset

1,470 employee records

35 features including demographic, compensation, tenure, performance, and satisfaction variables

Methodology
1. Data Preparation

Converted attrition variable to binary format

Engineered tenure, salary, and age bands

Performed categorical segmentation for risk profiling

2. KPI & Risk Modeling

Overall attrition rate calculation

Department-level attrition benchmarking

Relative Risk Score (segment attrition ÷ overall attrition)

Overtime Risk Multiplier

Tenure-based attrition segmentation

3. Financial Impact Estimation

Estimated replacement cost using salary-based assumption

Computed annual attrition cost exposure

Modeled cost-reduction scenarios based on targeted interventions

4. Visualization & Reporting

Interactive executive dashboard (Plotly)

KPI summary visualizations

Department risk heatmaps

Attrition trend segmentation charts

Key Analytical Findings

Overtime employees exhibit ~2x higher attrition risk relative to baseline

A tenure cliff effect is observed within the first 2 years

Department-level risk benchmarking identifies structural turnover concentration

Job satisfaction levels show inverse correlation with attrition probability

Attrition represents significant annual financial exposure under salary-based replacement modeling

Technical Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Business Value

This analysis demonstrates how workforce data can be transformed into:

Quantified attrition risk indicators

Financial impact estimates

Data-driven HR strategy recommendations

Structured decision-support insights

Future Scope

Multivariate risk interaction analysis

Predictive attrition modeling

Automated HR decision-support dashboard
