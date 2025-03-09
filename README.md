# Akuben


TASK 1
Using a data unification algorithm, the tech team at our client, Daikibo, has converted all telemetry data collected from its 4 factories:

Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 mins. Daikibo has been collecting this data for one month (May 2021) and they've shared this data in the form of a single JSON file.

The reason the client wanted to collect telemetry was to answer 2 questions:

In which location did machines break the most?
What are the machines that broke most often in that location?


Machine Failure Analysis - Daikibo Factories
 A data-driven approach to understanding machine failures across four global factories.

Project Overview
This project analyzes telemetry data collected from Daikibo's four factories to identify:
1️⃣ Which factory experienced the most machine failures?
2️⃣ Which machine type was most prone to failure in that factory?


Using Tableau, I visualized the dataset to extract key insights.

Dataset Information
Time Period: May 2021 (1 month of telemetry data)
Factories Covered:
Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Machines Tracked: 9 types (Each sending data every 10 mins)
 Data Format: JSON

Key Findings
   Factory with Most Failures:
Daikibo Factory Seiko (Osaka, Japan) had the highest failure rate.

   Most Affected Machine Type:
Laser machines experienced the most failures in Osaka.

Visualizations
I created Tableau dashboards to visualize and explore the failures across locations and machine types:

Project Structure
 data sets/ → Raw telemetry data (JSON)
 image/ → dashboard image (png)
 reports/ → Machine failure report (txt)
 README.md → This document

Tools Used
Excel (for data preprocessing)
Tableau (for visualization and dashboarding)
Git/GitHub (for version control)



Task 2: Employee Compensation Equality Analysis

Overview
This analysis evaluates fairness in employee compensation across different factories and job roles. The dataset includes an Equality Score, which quantifies how fair the salary distribution is within each job role.

We classified the Equality Score into three categories to better understand wage disparity:

Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)

Goals of the Analysis
Assess Pay Equality – Identify disparities in wages across different job roles and factories.
Classify Compensation Fairness – Group employees into Fair, Unfair, or Highly Discriminative categories based on their equality score.
Provide Visual Insights – Use Tableau to create interactive dashboards that highlight compensation trends.

Tools Used
Excel – Data cleaning, classification of equality scores, and dataset preparation.
Tableau – Data visualization and interactive dashboards for in-depth analysis.
Git/GitHub (for version control).

Dataset Information
Factory: The manufacturing facility where the employee works.
Job Role: The specific position held by the employee.
Equality Score: A score between -100 and +100 that measures fairness in compensation.
Equality Class: Categorization of fairness based on the score (Fair, Unfair, Highly Discriminative).

Files in the Repository
datasets/Task 5 Equality Table (xlsx) 
reports/Task 5 Equality Table updated(xlsx) – The dataset with the classified Equality Score.
reports/employee compensation fairness analysis (twb) – Tableau workbook with DASHBOARD analyzing pay fairness.
reports/factorywise compensation (twb) – Tableau visualization of factory-wise compensation patterns.
reports/job role vs equality (twb) – Job role comparison against Equality Score.
reports/distribution of equality scores(twb) – Distribution analysis of fairness across all roles.

Key Insights
Factories with Highly Discriminative scores show a significant wage gap.
Certain job roles have consistently Unfair pay scales, needing policy intervention.
Tableau dashboards visualize these trends, making it easier to identify areas for improvement.


Next Steps
Further analysis into causes of wage disparity.
Recommendations for achieving fair compensation across all roles.
Expanding the dataset with additional employee factors (experience, performance, etc.).
