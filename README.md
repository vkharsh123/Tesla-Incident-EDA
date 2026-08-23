# Tesla-Incident-EDA
Exploratory Data Analysis: Tesla Incident Demographics & Trends
Business Objective
The goal of this project is to perform an in-depth Exploratory Data Analysis (EDA) on a dataset of recorded Tesla incidents. By cleaning and processing the raw data, this analysis identifies critical temporal patterns and geographical hotspots, demonstrating end-to-end data wrangling and visualization capabilities.

Data Wrangling & Processing
Before analysis, the raw dataset was rigorously cleaned to ensure data integrity:
Data Reduction: Removed non-analytical and redundant columns (such as Case numbers, URLs, and specific deceased names) to optimize processing.
Standardization: Restructured and standardized column headers (e.g., renaming to Tesla_Driver, Other_Vehicle, Cyclists_Peds) for clean programmatic access.
Data Imputation: Handled missing values by replacing null indicators with appropriate numerical baseline data.  Feature Extraction: Extracted granular temporal features (Year, Month, Day) from raw date strings to allow for time-series aggregation.

Key Analytical Insights
Visualizations and grouped aggregations revealed several operational trends:
Year-Over-Year Trends: The data indicates that accident volume tends to increase annually.  
Seasonal Variance: Incident frequency is not evenly distributed; the highest number of recorded accidents occur in November and December.  
Geographical Concentration: The United States accounts for the overwhelming majority of incidents (213 recorded cases), followed distantly by China and Germany.  State-Level Hotspots: Within the US, incidents are heavily concentrated in California and Florida.  
<img width="1683" height="418" alt="event per country" src="https://github.com/user-attachments/assets/adc729e8-db24-427f-aec6-0215348c3eaa" />
<img width="1699" height="419" alt="event per state" src="https://github.com/user-attachments/assets/5541ef89-bb31-4cce-92cf-0b0b9483f203" />
<img width="1681" height="690" alt="event per month" src="https://github.com/user-attachments/assets/17c72d09-b67e-4abc-a5d2-46548692515c" />

Technical Stack
Languages & Libraries: Python, Pandas, NumPy.
Data Visualization: Matplotlib, Seaborn.
