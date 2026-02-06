# police-incident-analysis

## Overview
This project analyzes police incident data to examine patterns in incident classification, theft-related activity, and the distribution of violent and non-violent calls. The goal is to provide a clear, data-driven overview of public safety activity using aggregated incident-level metrics.

The dashboard was built in Power BI and uses distinct incident counts to avoid double-counting cases with multiple associated records.


## Key Questions Explored
- How do violent and non-violent incidents compare in frequency?
- How often do crime-related incidents occur compared to disturbances?
- What proportion of calls are domestic versus non-domestic?
- Which theft categories occur most frequently?



## Key Insights
- Non-violent incidents account for the majority of police calls  
- Crime-related incidents occur more frequently than disturbances  
- Domestic incidents represent a minority of total calls  
- Auto theft is the most common theft category  
- Using unique incident counts is essential due to multiple records per incident  



## Methodology
- Incidents were classified using DAX calculated columns based on signal descriptions
- Theft, disturbance, domestic, and violent classifications were derived using rule-based text matching
- Incident frequency was measured using unique incident numbers to prevent overcounting
- Visualizations were created in Power BI using bar charts, donut charts, and KPI cards



## Tools Used
- Power BI
- DAX (calculated columns and measures)
- Excel (source data)
- GitHub (version control and documentation)


## Files Included
- `dashboard/police_incidents_powerbi.pbix` – Interactive Power BI dashboard
- `data/police_report_2025.xlsx` – Source dataset
- `images/dashboard_overview.png` – Dashboard screenshot


## Notes
This project focuses on descriptive analysis and visualization. The findings reflect reported incidents within the dataset and do not imply causation or policy recommendations.
