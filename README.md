 Executive Recommendations Dashboard
Internship Project – Truvian Intelligence

 Project Overview
This project was part of my internship at Truvian Intelligence, where I was tasked with building a dynamic Excel dashboard to monitor and visualize Executive Board Recommendations. The dashboard provides real-time insights into recommendation status, priority, departmental involvement, and meeting timelines.

 Objective
Create a professional, user-friendly dashboard that allows executives to:

Track the status of each recommendation.

Monitor progress across departments.

View high priority items at a glance.

Analyze completion rates and overall implementation health.

 Data Structure
The raw dataset contained the following fields:

Recommendation ID

Recommendation Description

Department

Status (Not Started, In Progress, Completed)

Priority (Low, Medium, High)

Completion %

Meeting Date

I cleaned and structured this data using Excel tables and defined ranges to ensure dynamic references across visual elements.

 Dashboard Features
Metric	Description
 Total Recommendations	Total number of entries in the dataset
 Average Completion %	Calculated using AVERAGEIFS for dynamic filtering
 Latest Meeting Date	Uses MAXIFS to get the most recent meeting
 Status Breakdown	Count and percentage of recommendations by status
 Priority Breakdown	High, Medium, and Low priority counts
 Departments Involved	Count of unique departments working on recommendations

 Key Excel Techniques Used
Tables and Structured References for dynamic updates.

PivotTables to generate summary stats.

Slicers and Filters for interactive exploration.

Conditional Formatting to highlight high-priority items.

Formulas used:

COUNTIF, COUNTIFS

AVERAGEIFS

MAXIFS

UNIQUE, FILTER



 What I Learned
How to translate business goals into technical KPIs

Techniques to build clean, dynamic Excel dashboards

Importance of clear data labeling and visual storytelling

How to work with real-world, imperfect data

 How to Use This Dashboard
Open file.

Use slicers to filter by department, priority, or status.

Review summary metrics and visualizations for insights.

 Future Improvements
Connect Excel to a live data source (e.g., SharePoint or Power BI).

Add a Gantt chart to track implementation timelines.

Implement automatic alerts for overdue high-priority recommendations.

