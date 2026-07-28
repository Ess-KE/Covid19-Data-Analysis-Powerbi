# COVID-19 Global Dashboard Analysis | Power BI

## Project Overview

This project analyzes global COVID-19 trends using Power BI. The dashboard provides insights into confirmed cases, deaths, mortality rates, geographic distribution, and year-over-year growth patterns across 201 countries.

## Dataset source:

https://github.com/CSSEGISandData/COVID-19

## Datasets Used:

Confirmed Cases,
Death Cases,
Recovered Cases.

## Objectives
- Analyze global COVID-19 impact
- Identify countries most affected
- Track case and death trends over time
- Measure pandemic growth using Year-over-Year analysis
- Build an interactive dashboard for decision-making

## Tools Used
Power BI,
Power Query,
DAX.

## Key KPIs
- Total Confirmed Cases
- Total Deaths
- Death Rate (%)
- Countries Affected

## Key Insights
- Over 677 million confirmed cases and 7 million deaths were recorded globally.
- The United States reported the highest number of confirmed cases and deaths.
- COVID-19 growth peaked between 2020 and 2021 before slowing significantly.
- Global death rates declined from approximately 3.1% in 2020 to 1.0% in 2023.
- North America and Europe experienced the highest concentration of reported cases.
  
## Challenges Encountered
1. Data Structure. The dataset was initially stored in a wide format with dates as columns.

- Solution: Unpivoted date columns using Power Query.

2. Dataset Integration. Confirmed, Deaths, and Recovered datasets were stored separately.

- Solution: Merged datasets using common keys and validated matching records.

3. Cumulative Metrics. Confirmed and Death values were cumulative.

- Solution: Created Latest measures instead of summing cumulative values.

4. Recovery Data Quality. Recovery data contained inconsistencies and missing values.

- Solution: Excluded recovery-based KPIs from final analysis.

5. Outlier Death Rates. Some countries showed unrealistic mortality rates due to very small case counts.

- Solution: Treated as source-data limitations and interpreted results cautiously.

## Dashboard Preview
<img width="1423" height="850" alt="image" src="https://github.com/user-attachments/assets/89b2b6b3-d1eb-4ad1-b01f-b42ca16e3875" />
<img width="1422" height="844" alt="image" src="https://github.com/user-attachments/assets/b3f107b8-f8ad-436e-8b9c-698cbcb88bca" />



## Dashboard Screenshots

- <a href="https://github.com/Ess-KE/Covid19-Data-Analysis-Powerbi/blob/main/Executive%20Summary.jpeg"> View Executive Summary</a>

- <a href="https://github.com/Ess-KE/Covid19-Data-Analysis-Powerbi/blob/main/Trend%20Analysis.jpeg"> View Trend Analysis</a>

## Files Included
- <a href="https://github.com/Ess-KE/Covid19-Data-Analysis-Powerbi/blob/main/Covid.pbix">COVID19_Dashboard.pbix</a>

- <a href="https://github.com/Ess-KE/Covid19-Data-Analysis-Powerbi/blob/main/COVID-19%20Global%20Analysis%20%20Presentation.pptx">COVID19_Project_Presentation.pptx</a>

## Skills Applied
- Data cleaning and transformation using Power Query
- Time intelligence using Date tables and DAX
- Year-over-Year growth calculations
- Dashboard design and storytelling
- Data validation and quality assessment
