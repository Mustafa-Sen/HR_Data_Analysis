# HR Attrition Analysis & Turnover Prediction
This is an analysis of employee data in the dataset "HR_comma_sep.csv" to find out what contributes to employees leaving the company.

This project analyzes a Human Resources (HR) employee dataset to uncover factors related to employee attrition (turnover) and build a predictive model. We follow the CRISP-DM process - a well-known data science workflow - to ensure a structured approach: first understanding the business problem and data, then preparing and analyzing the data, and finally modeling and evaluating results. Throughout the notebook, we adhere to good coding practices (PEP8 naming, modular code, and ample documentation) to make our analysis clear and reproducible. The goal is not only to achieve high model performance, but also to yield actionable insights for HR decision-makers about why employees leave.

# Business Understanding and Questions

Employee attrition (employees leaving the company) can be costly. Understanding why attrition happens and being able to predict who might leave can help organizations proactively improve retention. In this analysis, we address the following key questions:

1. How often does attrition occur, and does it vary by group? - We examine the overall attrition rate (what percentage of employees left) as a baseline, and compare attrition across different departments and salary levels to see if certain groups have higher turnover.

2. What workplace factors are associated with employees leaving? - We explore differences in features like satisfaction level, performance evaluation, average hours, projects, etc., between employees who left versus those who stayed.

3. Are there combinations of factors that signal especially high attrition risk? - We analyze interactions (for example, satisfaction vs. performance) to identify if specific combinations of conditions lead to a spike in attrition.

4. Can we build a model to predict attrition, and which factors are most important? - Using machine learning, we create and compare models (baseline, logistic regression, tree-based models) to predict whether an employee will leave. We evaluate the models with appropriate metrics (ROC-AUC, PR-AUC, confusion matrix) and interpret which features drive the predictions (feature importance, partial dependence).
