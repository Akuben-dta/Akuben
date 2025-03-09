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


ANSWERS
Q1: In which location did machines break the most?
Look at Sheet 1 (Factory Chart). The factory with the highest "unhealthy" count (failures) is the one where machines broke the most.
?? From MY dashboard, it appears "Daikibo Factory Seiko (Osaka, Japan)" has the highest failures.


Q2: What are the machines that broke most often in that location?
Filter Sheet 2 (Device Type Chart) for only the highest-failure factory (Daikibo Factory Seiko).
Identify the machine type with the highest "unhealthy" count.
?? From My chart, it appears the "Laser" machine had the most 
failures.



TASK 2
We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:

Factory
Job Role
Equality Score (integer; ranging between -100 and +100; 0 is ideal)
Here is your task:

Create a 4th column (Equality class), classifying the equality score into 3 types:
Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)
Examples:

6 ? Fair
-9 ? Unfair
-30 ? Highly Discriminative
Please find the Equality Table you need to edit in the resources below. When you are done, upload the edited version of the file.

 
ANSWER
FILE CAN BE FOUND IN THE REPORT SECTION