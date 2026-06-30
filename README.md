# Axon-Healthcare-Dashboard (Excel, MySQL, Tableau, Power BI)

## Objectives
- Monitor patient demographics and clinical trends  
- Evaluate healthcare service efficiency  
- Track clinical quality and outcomes  
- Assess financial performance and sustainability  
- Enable data-driven decision making 

## Dataset used
- <a href="https://github.com/micky-abraham/Healthcare-Analytics-Project/blob/main/Data_Healthcare_Patient_D.xlsx">Dataset</a>

## KPIs
- Total Patients
- Total Doctors
- Total Visits
- Average Age of Patients
- Top 5 Diagnosed Conditions
- Follow-up Rate
- Treatment Cost per Visit
- Total Lab Tests Conducted
- Percentage of Abnormal Lab Results
- Doctor Workload
- Total Revenue
- Test Volume
- Patients by State

## Excel Dashboard 
- <a href="https://github.com/micky-abraham/Healthcare-Analytics-Project/blob/main/Project%20-%20Excel.xlsx">View Dashboard</a>

## Process
- Verify data for any missing values or anomalies, and resolving them in **Power Query**
- Made sure data is clean and consistent with respect to data type, data format and values used
- Establish Data Modeling by connecting the tables together in **Power Pivot**
- Create **Pivot Tables** according to the KPIs
- Insert Visuals based on Pivot tables into a single Dashboard and apply **slicer** to filter out dynamically

## Dashboard 
<img width="1777" height="865" alt="Screenshot 2026-06-30 151150" src="https://github.com/user-attachments/assets/f00c5a86-546d-4ea2-a96a-8999d999e6dd" />

## Tableau Dashboard 
- <a href="https://github.com/micky-abraham/Healthcare-Analytics-Project/blob/main/Project%20-%20Tableau.twbx">View Dashboard</a>

## Process
- Tables are placed in the **logical layer** and connected with noodles
- Relationships are defined by matching fields such as IDs
- Queries are generated dynamically based on the relationship settings
- Created graphs and visuals in seperate sheets and merged them in one dashboard
- Filters are added to get dynamic data in a range 

## Dashboard 
<img width="1403" height="802" alt="Screenshot 2026-06-30 151412" src="https://github.com/user-attachments/assets/e5d6197c-f6ef-41fa-a36d-674b12a696d3" />
 
## Power BI Dashboard
- <a href="https://github.com/micky-abraham/Healthcare-Analytics-Project/blob/main/Project%20-%20Power%20BI.pbix">View Dashboard</a>

## Process
- Ensured data consistency in types, formats, and values in Power 
- Built a **data model** by connecting tables in Power Pivot  
- Created KPIs and measures with **DAX formulas**  
- Designed visuals such as charts, cards, and donut layouts  
- Applied **slicers and filters** for dynamic, interactive dashboards

## Dashboard
<img width="1293" height="852" alt="Screenshot 2026-06-30 151533" src="https://github.com/user-attachments/assets/13d75ddd-5924-45d9-bf1f-3293cec0206d" />

## MySQL Script
- <a href="https://github.com/micky-abraham/Healthcare-Analytics-Project/blob/main/Project%20-%20SQL.sql">View Dashboard</a>

## Process
- Import data using **Table Data Import Wizard**
- Perform **data count validation** to ensure accuracy  
- Identified and removed **duplicate entries or null values**
- Performance testing using **explain analyze**

## Dashboard
<img width="1102" height="617" alt="Screenshot 2026-06-30 213402" src="https://github.com/user-attachments/assets/1ef6cd40-2aef-408c-8596-2a8368c97e14" />

## Project Insights
- Patient visits increased steadily across the year, but the follow‑up rate remained low and needs closer monitoring
- Treatment cost per visit showed slight growth, which should be kept in check to avoid unnecessary expense escalation
- Abnormal lab results accounted for 34% of tests shows there is a critical area that requires medical review and quality control
- Doctor workload is slightly higher for pediatrics and general medicine carried loads, suggesting resource balancing may be needed
- Revenue reached 30.65M, driven mainly by treatment costs, while diagnostic costs stayed stable and cost allocation should be tracked for sustainability
- Test volumes for CT scans and X‑rays were high, while blood and urine tests were lower ensuring balanced test utilization is important

## Conclusion
The dashboards show low patient follow‑up rates and high abnormal lab results, which hospitals can address through reminders and stricter lab protocols. Doctor workloads need balancing, especially in pediatrics and general medicine, by improving scheduling and resource allocation. Rising treatment costs should be monitored with audits and preventive care programs to keep expenses sustainable

