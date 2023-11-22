# Minnesota_Interstate_Traffic_Volume_Dashboard
# About Statement
The objective of this project is to develop an interactive data visualization dashboard to enhance an understanding of traffic patterns on the Minneapolis interstate. This project addresses the critical need to analyze and interpret traffic volume trends throughout the year, considering diverse time scales, weather conditions, and holidays. The goal is to provide actionable insights that will inform infrastructure decisions, ensuring the efficiency and safety of the interstate.
## Purpose of the Project:
The primary purpose of this project is to empower the Minnesota Department of Transportation with a comprehensive tool for monitoring and analyzing traffic patterns on the interstate. By visualizing data related to traffic volume, weather conditions, and holidays, the dashboard will facilitate informed decision-making regarding potential infrastructure changes. 
 ### Key objectives 
1.	Traffic Volume Analysis
Provide a detailed examination of traffic volume trends throughout the year, organized by year, month, week, day, and hour. This analysis will reveal patterns and help identify areas that may require infrastructure adjustments such as lane additions or changes.
2.	Weather Impact Assessment
 Investigate the correlation between traffic volume and weather conditions. By understanding how weather influences traffic behavior, the Department aims to enhance its ability to plan for adverse conditions and minimize disruptions on the interstate.
3.	Holiday Traffic Evaluation
 Examine traffic volume trends during different holidays to support planning for infrastructure updates. Identifying peak traffic periods on holidays will aid in scheduling construction activities to minimize disruptions and ensure a smooth traffic flow.

## About Data
The Minnesota Department of Transportation Data  has 9 Columns and 48205 Rows:


Column	Description	Data Type
Holiday	Type of Holiday	VARCHAR
Temperature 	Total Temperature	DECIMAL
rain	Rain Duration	INTEGER
snow	Snow Duration	INTEGER
clouds_all	Conditions of clouds	INTEGER
weather_main	The type of Weather	VARCHAR
weather_description	Describes the weather main	VARCHAR
date_time	The date of Traffic	TIMESTAMP
traffic_volume	Total Traffic	INTEGER


## Approach Used
This approach ensures that the data is prepared for analysis by addressing missing values and understanding the dataset through exploratory data analysis. The final step involves the use of Tableau to visually communicate the insights and patterns discovered during the analysis.
1.	Data Wrangling
Objective: Ensure data quality and handle missing values.
Steps:
Inspect the dataset for NULL values and missing data.
Employ data replacement methods to address missing or NULL values.
2.	Exploratory Data Analysis (EDA)
Objective: Answer project-specific questions and understand the dataset.
Steps:
Perform exploratory data analysis to gain insights into the data.
Address project aims and questions through statistical and visual exploration.
3.	Visualization using Tableau.
Objective: Present insights and patterns discovered during EDA in a visual format.
Steps:
Utilize Tableau for creating visualizations.
Communicate findings through charts, graphs, and dashboards.

## Business Question to Answer
•	Traffic volume throughout the year; ideally organized by year, month, week, day, and hour.
•	Traffic volume in different weather conditions.
•	Traffic volume on different holidays.

