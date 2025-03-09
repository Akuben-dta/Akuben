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
📊 A data-driven approach to understanding machine failures across four global factories.

Project Overview
This project analyzes telemetry data collected from Daikibo's four factories to identify:
1️⃣ Which factory experienced the most machine failures?
2️⃣ Which machine type was most prone to failure in that factory?

Using Tableau, I visualized the dataset to extract key insights.

Dataset Information
📅 Time Period: May 2021 (1 month of telemetry data)
🏭 Factories Covered:
Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
⚙️ Machines Tracked: 9 types (Each sending data every 10 mins)
📁 Data Format: JSON
Key Findings
✅ Factory with Most Failures:
🔹 Daikibo Factory Seiko (Osaka, Japan) had the highest failure rate.

✅ Most Affected Machine Type:
🔹 Laser machines experienced the most failures in Osaka.

Visualizations
I created Tableau dashboards to visualize and explore the failures across locations and machine types:

Factory Breakdown: Failure rates per location
Machine Type Breakdown: Failures per machine type at Seiko factory

Project Structure
📂 data sets/ → Raw telemetry data (JSON)
📂 image/ → Tableau visualizations
📂 reports/ → Machine failure report and analysis
📄 README.md → This document

Tools Used
Excel (for data preprocessing)
Tableau (for visualization and dashboarding)
Git/GitHub (for version control)
