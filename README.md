#  HR Analytics & Employee Attrition Dashboard

> An interactive **Power BI HR Analytics project** focused on
> understanding employee attrition patterns across departments, job
> roles, age groups, gender, education, job satisfaction, and overtime.

##  Project Overview

Employee attrition is an important HR metric because it helps
organizations understand where employee turnover is concentrated and
which workforce segments may require deeper investigation.

This project uses **Excel data, Power Query, DAX, and Power BI** to
transform employee-level HR data into an interactive dashboard and
presentation.

###  Business Objectives

-   Understand the overall scale and pattern of employee attrition.
-   Identify departments and job roles with comparatively high turnover.
-   Analyze attrition across age and gender groups.
-   Explore attrition across education fields.
-   Examine the relationship between job satisfaction and attrition.
-   Compare attrition between employees who work overtime and those who
    do not.
-   Build an interactive, decision-ready HR dashboard.
##  Dataset at a Glance

The analysis contains **1,470 employee records**.

  KPI                           Value
  ------------------------ ----------
  Total Employees               1,470
  Attrition                       237
  Active Employees              1,233
  Overall Attrition Rate       16.12%
  Average Age                37 years

The dataset records whether employees have left the organization and
contains demographic, job, education, satisfaction, and work-related
attributes used for analysis.
##  Dashboard

The Power BI dashboard provides an interactive overview of employee
attrition.

### Main Dashboard Components

-   Overall Employees
-   Attrition Count
-   Attrition Rate
-   Active Employees
-   Average Age
-   Attrition by Department
-   Employee Count by Age & Gender
-   Job Satisfaction Analysis
-   Attrition by Education Field
-   Attrition Rate by Age Group
-   Attrition by Job Role
-   Overtime-based Attrition Analysis
-   Education-category filtering
##  Key Insights

### 1. Overall Attrition

-   **237 out of 1,470 employees** are recorded as having left the
    organization.
-   The observed overall attrition rate is **16.12%**.
-   **1,233 employees** remain active.

### 2. Attrition by Department

-   **Sales** has the highest observed department attrition rate at
    **20.63%**.
-   **HR** follows at **19.05%**.
-   **R&D** has the largest absolute attrition count, with **133
    employees**.
-   Attrition count should be considered together with workforce size
    when comparing departments.

### 3. Attrition by Age & Gender

-   Employees **under 25** have the highest observed age-group attrition
    rate at **39.18%**.
-   The **25--34** age group contributes the largest attrition count,
    with **112 employees**.
-   Male attrition count is **150**, compared with **87** for female
    employees.
-   Observed attrition rate is **17.01% for males** and **14.80% for
    females**.

### 4. Attrition by Job Role

-   **Sales Representative** has the highest observed role-level
    attrition rate at **39.76%**.
-   Laboratory Technician: **23.94%**
-   Human Resources: **23.08%**
-   Research Director has the lowest observed rate at **2.50%**.

### 5. Education & Job Satisfaction

-   **Life Sciences** has the largest attrition count at **89
    employees**.
-   Human Resources has the highest education-field attrition rate at
    **25.93%**, although its workforce is relatively small.
-   Employees with job satisfaction rating **1** show an observed
    attrition rate of **22.84%**.
-   Employees with satisfaction rating **4** show an observed attrition
    rate of **11.33%**.

> **Note:** These findings represent associations in the dataset and
> should not be interpreted as proof that job satisfaction alone causes
> attrition.

### 6. Overtime

Overtime shows a notable difference in observed attrition:

  Overtime Status     Observed Attrition Rate
  ----------------- -------------------------
  Yes                                  30.53%
  No                                   10.44%

The observed attrition rate is approximately **2.9x higher** among
employees who work overtime.

This association should be investigated alongside factors such as
workload, role, tenure, compensation, and promotion history.
##  Business Recommendations

Based on the analysis, the project highlights several areas for further
HR investigation:

1.  Investigate workload and career-growth factors in high-attrition
    roles.
2.  Develop targeted onboarding and retention initiatives for younger
    employees.
3.  Monitor overtime and workload patterns across teams.
4.  Use employee feedback to understand areas associated with lower job
    satisfaction.
5.  Compare attrition with compensation, tenure, and promotion
    information.
6.  Use the Power BI dashboard for regular HR monitoring and exploratory
    analysis.
## ️ Tools & Technologies

  Tool / Technology     Purpose
  --------------------- -------------------------------------------
  **Microsoft Excel**   Data source and initial dataset
  **Power Query**       Data transformation and preparation
  **Power BI**          Dashboard development and visualization
  **DAX**               Measures, calculations, and KPIs
  **PowerPoint**        Project presentation and storytelling
  **GitHub**            Project documentation and version control
##  Project Structure

``` text
HR-Analytics-Employee-Attrition/
│
├──  HR Analytics Dashboard.pbix
├──  HR Data.xlsx
├──  HR_Analytics_Employee_Attrition_Presentation.pptx
├── ️ IMG_20260917_070656.jpg
└──  README.md
```

> Rename the Power BI file in the structure above to match the actual
> `.pbix` filename you upload to the repository.
##  Dashboard Workflow

``` text
Excel HR Dataset
       |
Power Query
       |
Data Cleaning & Transformation
       |
DAX Measures & Calculations
       |
Power BI Dashboard
       |
HR Insights & Recommendations
```
##  Key Metrics

The dashboard focuses on metrics such as:

**Attrition Rate**

``` text
Attrition Rate = Attrition Employees / Total Employees x 100
```

For this dataset:

``` text
237 / 1470 x 100 = 16.12%
```

Other important metrics include:

-   Total Employees
-   Active Employees
-   Attrition Count
-   Average Age
-   Department Attrition Rate
-   Job Role Attrition Rate
-   Age Group Attrition Rate
-   Job Satisfaction-based Attrition Rate
-   Overtime-based Attrition Rate
##  What I Learned

Through this project, I practiced:

-   Cleaning and preparing HR data.
-   Building an analytical data model in Power BI.
-   Creating DAX measures and KPIs.
-   Designing an interactive dashboard.
-   Using charts and filters to explore employee segments.
-   Comparing attrition counts with attrition rates.
-   Translating data analysis into business-focused insights.
-   Presenting analytical findings through PowerPoint.
-   Documenting a complete analytics project for GitHub.
## ️ Important Interpretation Note

The dashboard describes **observed patterns and associations in the
dataset**. The results do not by themselves establish causal
relationships.

For example, the higher attrition rate among overtime employees
indicates an association that could be investigated further using
additional variables such as workload, tenure, compensation, job role,
and promotion history.
##  How to Use This Project

1.  Download or clone this repository.
2.  Open the Excel dataset to review the source data.
3.  Open the `.pbix` file in **Microsoft Power BI Desktop**.
4.  Refresh the data if required.
5.  Interact with the dashboard filters and visualizations.
6.  Review the PowerPoint presentation for the project walkthrough and
    findings.
##  Project Author

**Keshav Kumar Aggarwal**

**Project:** HR Analytics & Employee Attrition Dashboard\
**Domain:** HR Analytics / Data Analytics / Business Intelligence\
**Tools:** Power BI | Power Query | DAX | Excel
## ⭐ Project Summary

This project demonstrates how raw HR employee data can be transformed
into an interactive **Power BI dashboard** that highlights employee
attrition patterns and provides a structured foundation for HR
investigation and decision-making.
