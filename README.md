# Hr-Analysis
# Capstone Project: Employee Attrition Analysis and Retention Strategy Using Power BI

## 1. Project Background

Employee retention is an important concern for organizations because losing employees can lead to recruitment expenses, training costs, loss of organizational knowledge, and disruptions to productivity.

However, an organization cannot develop effective retention strategies simply by counting the number of employees who leave. It needs to understand how attrition varies across departments, job roles, employee tenure, satisfaction levels, compensation, and other relevant workforce characteristics.

This project will apply data analytics to employee records to identify attrition patterns, investigate factors associated with employee exits, and provide evidence-based recommendations that can support human resource management.

## 2. Problem Statement

The organization lacks a clear, data-driven understanding of its employee attrition patterns and the workforce characteristics associated with employees leaving.

Without a structured analysis of employee data, management may struggle to identify areas requiring attention, determine which employee groups experience higher attrition, and prioritize appropriate retention initiatives.

The project will analyze employee data using Microsoft Power BI to establish the scale of attrition, investigate differences across workforce groups, and develop recommendations that can support better employee-retention decisions.

## 3. Project Aim

To analyze employee attrition patterns using Microsoft Power BI, identify workforce characteristics associated with employee exits, and recommend data-driven strategies for improving employee retention.

## 4. Project Objectives

The project will seek to:

1. Determine the organization's employee population and overall attrition rate.
2. Examine how attrition varies across departments and job roles.
3. Investigate the relationship between employee tenure and attrition.
4. Assess whether job satisfaction differs between employees who leave and those who remain.
5. Examine the relationship between compensation and attrition, where the necessary data is available.
6. Investigate differences in attrition across relevant demographic and workplace categories.
7. Identify workforce groups that may require further investigation.
8. Develop an interactive Power BI dashboard for communicating the findings.
9. Recommend practical employee-retention strategies based on the results.

## 5. Research Questions

The analysis will be guided by the following questions:

1. What is the organization's overall employee attrition rate?
2. Which departments and job roles have the highest attrition counts and rates?
3. How does attrition vary across employees with different lengths of service?
4. Is job satisfaction associated with employee attrition?
5. Is there an association between monthly income and attrition?
6. How does attrition vary across age groups and gender categories?
7. Are there differences in attrition between employees with different job levels or work-related characteristics?
8. Which workforce groups should management prioritize for further investigation?
9. What retention strategies are most appropriate given the patterns identified in the data?

These questions will be answered using the available dataset. Questions that cannot be supported by the available fields will be excluded or clearly identified as limitations.

## 6. Data Source and Requirements

The dataset will likely be obtained from Kaggle, subject to identifying and verifying a suitable employee attrition dataset.

The dataset should contain employee records, a reliable attrition indicator, and relevant workforce characteristics.

Potential variables include:

| Variable | Analytical purpose |
|---|---|
| Employee ID | Identify unique employee records |
| Attrition | Distinguish employees who left from those who stayed |
| Department | Compare attrition across departments |
| Job role | Identify differences across job functions |
| Years at company | Examine the relationship between tenure and attrition |
| Job satisfaction | Investigate satisfaction and retention patterns |
| Monthly income | Examine compensation-related patterns |
| Age | Compare attrition across age groups |
| Gender | Examine differences across recorded gender categories |
| Job level | Investigate attrition by organizational level |
| Work-life balance | Explore its association with attrition, if available |
| Distance from home | Examine potential commuting-related patterns |

The final list of variables will depend on the selected dataset. The project will document the dataset title, author or uploader, source URL, description, and applicable usage conditions.

## 7. Project Methodology

### Phase 1: Business Understanding

Define the business problem, identify the stakeholders, establish the research questions, and determine which metrics would help HR understand employee attrition.

### Phase 2: Data Acquisition

Obtain a suitable employee dataset, likely from Kaggle. Review its documentation and determine whether it contains sufficient information to answer the research questions.

### Phase 3: Data Preparation

Use Power Query in Power BI to:

- Inspect the dataset structure and data types.
- Check for missing values and duplicate employee records.
- Identify inconsistent category labels.
- Validate the attrition field and other key variables.
- Examine unusual values and determine how they should be handled.
- Confirm that employee records are suitable for the intended analysis.

Any exclusions or transformations will be documented.

### Phase 4: Exploratory and Diagnostic Analysis

Analyze the data to establish baseline attrition metrics and investigate patterns across departments, tenure, satisfaction, compensation, and other available characteristics.

Compare both attrition counts and attrition rates. Where appropriate, examine combinations of variables to determine whether apparent differences remain when other workforce characteristics are considered.

### Phase 5: KPI Development

Create calculated measures using DAX in Power BI. Validate the measures against the underlying employee records before using them in visualizations.

### Phase 6: Dashboard Development

Build an interactive Power BI report that presents the key metrics, highlights meaningful patterns, and allows users to investigate attrition across different workforce categories.

### Phase 7: Interpretation and Recommendations

Interpret the findings in relation to the business questions. Develop recommendations based on the evidence and distinguish associations from causal explanations.

### Phase 8: Validation and Presentation

Check calculations, verify dashboard interactions, document limitations, and prepare a concise presentation of the findings and recommendations.

## 8. Key Performance Indicators

The following KPIs will be developed where the data supports them.

**Overall attrition rate**

Attrition rate = Number of employees who left ÷ Defined employee population × 100.

The denominator must match the dataset's population definition. For a historical HR dataset, this may be the total employee records in the study rather than the organization's current workforce.

**Other KPIs**

- Total employees represented in the dataset.
- Number of employees who left.
- Number of employees who stayed, where status is available.
- Attrition rate by department.
- Attrition rate by job role.
- Attrition rate by tenure group.
- Attrition rate by satisfaction category.
- Attrition rate by age group and gender.
- Average tenure among employees who left and those who stayed.
- Average monthly income by attrition status, if available.

These measures will allow the analysis to compare workforce groups consistently.

## 9. Proposed Analytical Approach

The analysis will follow the business questions rather than assume particular results in advance.

**Department analysis:** Compare attrition rates across departments and job roles to determine whether exits are concentrated in particular areas.

**Tenure analysis:** Group employees by years of service and compare attrition across those groups to determine whether exits are more common at particular career stages.

**Satisfaction analysis:** Compare satisfaction distributions between employees who left and those who stayed. Investigate whether lower satisfaction is associated with higher attrition.

**Compensation analysis:** Compare income distributions across attrition categories and, where appropriate, account for differences in job level and role.

**Demographic analysis:** Compare attrition across relevant age and gender groups while avoiding unsupported conclusions about the reasons behind any observed differences.

**Combined analysis:** Examine whether certain combinations of characteristics are associated with higher attrition. For example, the analysis may investigate whether a particular department and tenure group has a different attrition rate from the overall population.

## 10. Power BI Dashboard Design

The dashboard structure will be determined by the research questions and the results of the analysis.

**Page 1: Workforce Overview**
- Employee population.
- Number of employees who left.
- Overall attrition rate.
- Attrition by department.
- High-level workforce comparisons.

**Page 2: Department and Job Role Analysis**
- Attrition counts and rates by department.
- Attrition by job role.
- Comparison of workforce sizes and attrition rates.
- Filters for relevant workforce categories.

**Page 3: Tenure and Satisfaction**
- Attrition by years of service.
- Satisfaction by attrition status.
- Tenure comparisons between employees who left and those who stayed.

**Page 4: Compensation and Workforce Characteristics**
- Income comparisons by attrition status.
- Attrition across job levels and age groups.
- Other available employee characteristics relevant to the research questions.

Interactive slicers will allow users to explore the results by department, job role, tenure, and other relevant categories.

## 11. Expected Business Value

The project is intended to help the organization:

- Establish a reliable baseline for employee attrition.
- Identify departments and workforce groups requiring further investigation.
- Understand how attrition varies with tenure and satisfaction.
- Examine potential compensation-related patterns.
- Prioritize retention initiatives based on evidence.
- Monitor workforce metrics through an interactive reporting tool.

The project will not assume that any specific factor causes employees to leave. If the dataset is observational, the analysis will identify patterns and associations rather than prove causation.

## 12. Project Timeline

| Week | Activities |
|---|---|
| Week 1 | Define the problem, select the dataset, and assess data quality |
| Week 2 | Prepare the data and develop validated KPIs in Power BI |
| Week 3 | Conduct the analysis and build the interactive dashboard |
| Week 4 | Validate findings, develop recommendations, and prepare the final presentation |

## 13. Deliverables

The primary deliverable will be a **fully interactive Power BI dashboard**.

Supporting deliverables will include:

- Power BI project file (`.pbix`).
- Project report documenting the problem, methodology, findings, and recommendations.
- Dataset source citation and URL.
- Final presentation summarizing the analysis and business implications.

## 14. Success Criteria

The project will be considered successful if it:

- Answers the research questions supported by the dataset.
- Calculates employee attrition metrics correctly.
- Compares attrition using both counts and rates.
- Presents the findings through a clear, interactive Power BI dashboard.
- Provides recommendations linked to the actual results.
- Documents data limitations and avoids unsupported causal claims.

## Conclusion

This capstone project will use employee data to investigate workforce attrition and identify patterns that can inform employee-retention decisions. Through structured analysis and an interactive Power BI dashboard, the project will help translate HR data into actionable business insights.

The final conclusions and recommendations will be determined only after the dataset has been examined and the analysis completed.

## Dash board  
<img width="834" height="450" alt="Screenshot 2026-10-25 164327" src="https://github.com/user-attachments/assets/b92de62e-8f21-48cd-876e-9cad0287cb60" />

