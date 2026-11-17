# Ikea_gifting_Dashboard
Interactive Power BI dashboard analyzing e-commerce sales, RFM customer segmentation, and retention cohorts to uncover churn risks, high-value customer tiers, and segment-level revenue performance.


Architecture & Data Modeling
Data Transformation: Processed transactional records, parsed dates (InvoiceDate), established custom hierarchies (Date Hierarchy across Year, Quarter, and Month), and resolved data types.

Metric Engineering (DAX): Formulated key performance measures including:

Total Revenue

Total Customers

Churned %

Avg Customer Value

RFM scoring distributions (Average of R_Score, Average of F_Score, Average of M_Score)

Dynamic Canvas Architecture: Utilized the Selection Pane, Bookmarks, and a Bookmark Navigator to create an interactive multi-view toggle on a single page, switching seamlessly between Revenue Analytics and Customer Analytics without reloading the report.

Key Dashboard Views
1. Business Overview Page
KPI Header Cards: Executive snapshot monitoring core health metrics (Total Customers: 6K, Total Revenue: $17.4M, Churn Rate: 50.86%, Average Customer Value: $2.95K).

Global Slicers: Universal multidimensional filtering across Month, Quarter, Year, Country, Segment, and IsChurned.

Revenue vs. Customer Toggle:

Revenue View: Evaluates revenue distribution across customer segments, retention splits via pie/stacked charts, and historical revenue run-rates by month, quarter, and year.

Customer View: Tracks customer volume distribution across segments, churn/retention ratios by cohort, and customer acquisition trend lines over time.

2. RFM Analysis Page
Segment Performance Summary (Matrix Table): Granular matrix evaluating customer segments (Champions, Loyal, At Risk, Lost, Need Attention, New) against volume, revenue contribution, and average R/F/M score breakdowns.

Segment by Average Customer Value: Clustered column visualization highlighting spend concentration per tier to guide targeted retention programs.

Cohort Churn Trajectories: Multi-timeline analysis tracking churn percentage evolution across Monthly, Quarterly, and Annual windows.

Tech Stack & Tools
BI Tool: Microsoft Power BI Desktop

Data Analytics Concepts: RFM Segmentation, Cohort Retention Analysis, Customer Churn Telemetry, Sales Run-Rate Tracking

Power BI Features: DAX Measures, Bookmarks & Selection Grouping, Bookmark Navigators, Matrix Custom Padding/Formatting, Custom Canvas Themes
