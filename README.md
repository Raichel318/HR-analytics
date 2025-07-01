# HR Analytics Dashboard

This Power BI Interactive  dashboard provides a sharp view into key HR metrics, helping business leaders track workforce size, compensation benchmarks, and leave utilization. It’s designed to empower strategic decisions in staffing, budget allocation, and employee engagement.

# Key Performance Indicators (KPIs)

1) Headcount: Total number of current employees across departments and regions

2) Average Salary: Mean compensation, reflecting payroll trends across roles

3) Average Leave Balance: Indicates typical accumulated leave per employee

4) Employees with Leave > 20 Days: Flags high leave balances that may impact scheduling or reflect long tenure

These KPIs are displayed using modern card visuals, with reference labels and conditional colors to provide instant status recognition.

# Graphs & Visual Breakdown
1. 📊 Monthly Headcount Trend
A line chart showing net changes in employee count over time (joins vs exits)

Integrated with a zoom slider for navigating long time ranges

2. 🧭 Department-Wise Employee Distribution
Stacked bar chart breaking down headcount by department or business unit

Includes field parameters for switching between groupings (e.g., by region, job role)

3. 💰 Salary Distribution Histogram
Histogram visual showing frequency of salaries across defined ranges

Created using the group feature for intuitive binning

4. 🏖️ Leave Balance Table
Detailed table displaying individual leave balances with conditional formatting

Highlights employees with over 20 days of leave using bold color cues

5. 📍 Country-wise Headcount Breakdown
Bar chart displaying employee counts across regions

Tooltips show country-specific averages (salary, tenure, leave)

6. 🚻 Gender Ratio Pie Chart
Visual representation of gender diversity

Dynamically linked to slicers and filters

# Technical Features

1) Dedicated Measure Table: Centralized DAX logic for key HR metrics like headcount, average salary, and leave balance

2) Advanced DAX Calculations: Used for computing averages, thresholds (e.g., leave > 20 days), and KPI indicators

3) Slicer Panel: Allows filtering by department, region, gender, and role for flexible exploration

4) Card Visuals: Showcased KPIs like total headcount, average salary, average leave balance, and employees with high leave

5) Custom Charts: Includes line charts, bar graphs, and pie charts for headcount trends, salary distribution, departmental split, and gender ratio

6) Conditional Formatting: Applied to leave balance tables to highlight employees exceeding the 20-day threshold
7) Zoom Slider Integration: Enhances time-based visuals for headcount change tracking

 <img width="1180" alt="HR Analytics dashboard" src="https://github.com/user-attachments/assets/2a0e283e-f23e-46c3-98d3-25f8bb6ec4df" />




