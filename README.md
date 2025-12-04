# Sales-Operations-Planning-KPI-Dashboards
A collection of operational dashboards used to monitor throughput, labor productivity, and internal damages across multiple automotive processing facilities.

---

This repository contains a suite of S&amp;OP KPI dashboards designed to monitor operational performance across customer throughput, labor productivity, and internal vehicle damages. The dashboards are built to support leadership and planners with trend insights, goal tracking, and variance analysis at the facility and carline level.

---

## Dashboards

### 1. Customer Throughput Dashboard
Tracks how efficiently vehicles move through the operation and how well customer goals are being met.

**Key Metrics**
- Released to Goal (actual released units vs. customer goal)
- Staged to Goal (units staged vs. goal)
- Hours Completed to Goal (actual hours vs. planned/goal hours)
- Percentage of Customers Meeting Goals

---

### 2. Productivity Dashboard
Measures labor efficiency, staffing accuracy, and operational execution.

**Key Metrics**
- Scheduled vs. Needed Labor (scheduled headcount/hours vs. required labor)
- Productivity (produced minutes ÷ actual minutes worked)
- Percentage of Daily Plans Closed
- Percentage of Days Fully Staffed

---

### 3. Internal Damages Dashboard
Monitors internal quality performance and the financial impact of damage incidents.

**Key Metrics**
- Damage Rate (damaged units ÷ total inventory)
- Damage Severity (average cost per damaged vehicle)

---

## Shared Dashboard Features

### Trend Analysis
All dashboards include:
- Week-over-week and month-over-month trend indicators  
- Multi-period analysis for:  
  - Current Week  
  - Previous Week 1  
  - Previous Week 2  
  - Previous Week 3  
  - Month-to-Date (MTD)  
  - Quarter-to-Date (QTD)  
  - Year-to-Date (YTD)

### Filters
- Date range selection  
- Facility selection  
- Carline selection  

### Summary Tables
- Breakdown of KPIs by carline  
- Clean formatting for export and reporting  
- Color-coded performance indicators for WoW% and MoM% changes  

### Variance Indicators
- WoW% and MoM% deltas  
- Positive/negative changes highlighted using color logic inside the dashboards

---

## Technical Highlights

- Star-schema semantic modeling  
- DAX measures for dynamic trends and KPI variance  
- Performance optimization (DirectLake/Import modes)  
- Automated refresh scheduling  
- Row-level filtering for facility and carline  

---

## Business Value
These dashboards support S&OP leaders by:
- Improving labor planning and staffing alignment  
- Highlighting throughput bottlenecks  
- Tracking customer goal attainment  
- Monitoring internal quality and damage costs  
- Enabling data-driven decision-making across facilities  

---

## Contact
**Joel Perez**  
Data Analyst / Power BI Developer
jebjobportal@gmail.com
linkedin.com/in/joel-perez-43617b257
