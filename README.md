# Excel-Dashboard
An interactive Excel dashboard that tracks the daily sales performance of 200 sales executives across 5 Indian states, built using pivot tables, slicers, and multiple chart types (bar, pie, and line charts).


📊 Sales Executive Performance Dashboard (Excel)
![Dashboard Preview]<a href="https://github.com/whyash27/Excel-Dashboard/blob/main/Screenshot%202026-07-18%20112910.png"></a>
## Dataset used
- <a href="https://github.com/whyash27/Excel-Dashboard/blob/main/Sales_Report.xlsm"></a>

📁 Project Overview
This project analyzes 5-day sales data for a sales team and presents it through a single-page, interactive dashboard. A region slicer lets you filter every dashboard, chart, and table on the sheet simultaneously, making it easy to drill down into performance by state.
File: `Sales_Report.xlsm`
🗂️ Workbook Structure
Sheet	Description
`RAW DATA`	Source data — 200 sales executives with daily sales (Day 1–Day 5), total sales, target, target hit %, and away-from-target %
`DASHBOARD`	The interactive dashboard with slicers, pivot tables, and charts
Raw data columns: Emp Code, Sales Executive, Region, Day 1–Day 5, Total Sales, Target, Target Hit %, Away From Target %
🎛️ Slicer
A Region slicer (Gujarat, Karnataka, Maharashtra, Tamil Nadu, Uttar Pradesh) is connected to all pivot tables and charts on the dashboard. Selecting a state instantly filters every dashboard section to show that region's data only.
📈 Dashboard Sections
The dashboard is split into 4 mini-dashboards, each toggleable via its own checkbox control:
Dashboard 1 – Top 5 by Total Sales
Pivot table + bar chart showing the 5 executives with the highest total sales.
Dashboard 2 – Bottom 5 by Total Sales
Pivot table showing the 5 executives with the lowest total sales.
Dashboard 3 – Top 5 by Target Hit %
Pivot table + pie chart showing the executives with the highest percentage of target achieved.
Dashboard 4 – Away From Target %
Pivot table + line chart showing how far each executive is from hitting their target.
🛠️ Excel Features Used
Pivot Tables (for dynamic top/bottom-N summaries)
Pivot Charts — Bar Chart, Pie Chart, Line Chart
Slicers (linked to multiple pivot tables via Report Connections)
Form Control Checkboxes (to toggle individual dashboard sections)
Conditional/data label formatting for readability
🚀 How to Use
Download `Sales_Report.xlsm` from this repository.
Open it in Microsoft Excel (macros/VBA content — enable editing & content when prompted).
Go to the DASHBOARD sheet.
Click any state in the Region slicer to filter all four dashboards at once.
Use the checkboxes above each dashboard to show/hide individual sections.
> ⚠️ Note: This file uses the `.xlsm` (macro-enabled) format. Enable macros/content when opening it for full functionality.
📌 Key Insights (Sample)
Total sales and target-hit performance vary noticeably by region and executive.
The bottom-5 and away-from-target views help quickly flag underperforming executives who may need support or coaching.
The top-5 views highlight consistent high performers for recognition or best-practice sharing.
🧰 Tools Used
Microsoft Excel (Pivot Tables, Pivot Charts, Slicers, Form Controls)
