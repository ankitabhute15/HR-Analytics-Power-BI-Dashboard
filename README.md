# HR-Analytics-Power-BI-Dashboard

### Description
An HR Analytics dashboard leveraging Power BI to transform attendance data into meaningful insights that drive HR performance and strategic planning.

### Objective
Automate and visualize attendance data across April–June to provide actionable insights on employee presence, WFH, sick leaves, and absentee patterns.

### Dashboard
<img width="810" height="505" alt="HR_Analytics_Dashboard" src="https://github.com/ankitabhute15/HR-Analytics-Power-BI-Dashboard/blob/main/HR_Analytics_Dashboard.PNG" />

### Dataset Used
<a href="https://github.com/ankitabhute15/HR-Analytics-Power-BI-Dashboard/blob/main/Attendance-Sheet-2022-2023.xlsx">Dataset</a>

### Dataset Overview
Excel file with employee attendance data across multiple monthly sheets (April–June).
Data attributes include:
- Employee Code & Name
- Daily Attendance Values: P, WFH, HWFH, SL, HSL, WO, HO
- Date-wise records for each employee

### Data Transformation (Power Query)
- Dynamically combined all monthly sheets using a parameter-based function
- Used Unpivot to convert date columns into a structured tabular format
- Cleaned & standardized attendance classification
- Created final consolidated table: Final Data

### Key Features
- Interactive slicers for Employee, Department, Team, and Date
- KPI cards for Total Working Days, Present Days, WFH, SL, and Absentee %
- Attendance trend analysis using stacked bar charts and matrices
- Employee-wise comparison for presence and absenteeism
- Weekday-wise and monthly attendance visualizations
- WFH and leave pattern insights

### Key DAX Measures
- Total Working Days: Days excluding weekly offs & holidays
- Present Days: Presence + WFH (1) + Half WFH (0.5)
- Present %: Present Days/Total Working Days
- WFH Count & WFH %: Tracks remote working trends
- SL Count & SL %: Tracks sick leave trends
- Absent Days & %: Indicates workforce availability

### Questions(KPIs)
- What is the overall attendance %?
- How many days were employees Present, WFH, or on Leave?
- Which weekdays have the highest WFH or Sick Leave?
- Who are the employees with low presence or high absenteeism?
- How do attendance trends vary across April–June?
- Which teams or departments maintain the best attendance?
- What is the ratio of Present Days to Total Working Days per employee?
- How do absentee patterns differ by day or month?

### Tools & Skills Used
- Power BI Desktop
- Power Query (Data cleaning & Automation)
- DAX (KPIs & business logic)
- Excel (raw data)

### Insights Delivered
- Provides visibility into overall attendance health
- Identifies weekdays with higher WFH or SL frequency
- Highlights employees with low presence / high absenteeism
- Shows attendance trends across the quarter (Apr–Jun)

### Conclusion
This HR Analytics dashboard automates attendance data processing and delivers actionable insights to support HR decision-making and improve workforce productivity.
