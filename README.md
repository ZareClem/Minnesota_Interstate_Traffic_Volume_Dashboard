# Minnesota_Interstate_Traffic_Volume_Dashboard
# About Statement
[Minnesota Traffic Volume Dashboard](https://public.tableau.com/app/profile/clement.zare/viz/MinnesotaTrafficVolumeDashboard_17004833764790/MinnesotaTrafficVolumeDashboard#3)

The objective of this project is to develop an interactive data visualization dashboard to enhance an understanding of traffic patterns on the Minneapolis interstate. This project addresses the critical need to analyze and interpret traffic volume trends throughout the year, considering diverse time scales, weather conditions, and holidays. The goal is to provide actionable insights that will inform infrastructure decisions, ensuring the efficiency and safety of the interstate.

The dashboard for this project has four charts and a legend. These charts include Traffic volumes by month per year, Traffic volumes by hour of the day, Traffic volumes organized by weather patterns, and a circle chart for Holidays with the highest traffic. Together, these charts address the stakeholders’ main interests: comparing the traffic volume at different points in time and at different timescales, and examining holiday and weather patterns throughout the year. 

The legend specifies a separate color for each of the three years represented in the data. This visualization uses only three years of data to prioritize simplicity. If these charts featured data from all the years, there would be too many lines and bars. This would make it much harder to read and, therefore, much less effective as a visualization. Because the charts use data from the same years, the color schema can be consistent across all the charts. This way, the orange line in one chart corresponds to the same year as the orange bars in another.
![image](https://github.com/ZareClem/Minnesota_Interstate_Traffic_Volume_Dashboard/assets/138980152/5cedf244-2ede-4384-be22-58f8ee17d4e0)
In this dashboard, the line chart is placed at the top, alongside the legend. Since the legend applies to each of the charts, it’s important to place it at the top of the visualization. There is a bar chart representing weather patterns and a circle chart representing national holidays in the United States. 
The heat map represents the traffic volumes by hours of the day. Because a large amount of data is being visualized at once, this chart is larger than the others so it can be viewed more easily.
The line chart and heat map represent two of the timescales in which the stakeholder is most interested: the monthly timescale and the weekly timescale. In these charts, it can be viewed which months and days of the week have the highest traffic volume. You can also find other trends: based on the line chart, it seems like the traffic volume for 2017 was generally higher than in 2016. 


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

![image](https://github.com/ZareClem/Minnesota_Interstate_Traffic_Volume_Dashboard/assets/138980152/823fdb03-ca27-43c4-ba32-0619a6fcf6f7)

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
1. Traffic volume throughout the year; ideally organized by year, month, week, day, and hour.

2.Traffic volume in different weather conditions.
	
3. Traffic volume on different holidays.

## Chart Analysis
### Traffic Volumes by month per year
•	This line chart illustrates a comparison of traffic volumes between consecutive years for each month. The chart addresses the inquiry: Which month typically experiences the highest traffic volume? The Date Time dimension is employed with a filter set to display the Month timescale. Additionally, the chart aggregates the sum of traffic volume across each period, resulting in a consolidated total for each monthly interval. Each data point on the chart reflects the overall number of cars on the road throughout an entire month.
•	The chart features three lines representing the years 2016, 2017, and 2018.
You can interact live  with the chart in Tableau [Here]
![image](https://github.com/ZareClem/Minnesota_Interstate_Traffic_Volume_Dashboard/assets/138980152/afdc7954-fb72-4b1e-985e-c52251107109)

### Traffic volumes by hour
•This heat map breaks down traffic concentration for each day and hour of each month. As you scroll through the visualization, the chart automatically updates to display each month’s data. This chart lets you compare each day and hour of traffic to the next, detailing traffic volume down to the hour. Columns in this heat map represent the day of the month and rows represent the time of day. Higher concentrations of traffic are represented by the color of each square in the heat map, with orange demonstrating a higher volume while the darker blue squares indicate less traffic.  
•You can interact live with the Heat Map in Tableau [Here]
![image](https://github.com/ZareClem/Minnesota_Interstate_Traffic_Volume_Dashboard/assets/138980152/8bc8db13-8aa6-4caf-aa1d-476bafdfa02d)

### Traffic volumes by weather pattern
•	This bar chart displays yearly traffic volume grouped by weather type. I included a date time filter that spans the years 2016 through 2018, I represented total traffic volume for those years and grouped it by weather type. For example, in those years, there were 24 million cars on the road during days with clear weather, while traffic volume decreased to 10 million during rainy weather. This also answers the  question about the effect that weather has on traffic.
•You can interact live with the Bar Chart in Tableau [Here]
![image](https://github.com/ZareClem/Minnesota_Interstate_Traffic_Volume_Dashboard/assets/138980152/e9079212-4c76-4867-8463-2f4abeafe409)

### Holidays with highest traffic
•I created a Custom column that specifies which entries are on holidays. I used the calculation: “if [Holiday] = "None" then null else "X" end”. This will create a column that is used to make a chart that compares only holiday traffic, using the circle chart.
•This chart uses color and size to compare the holidays with the highest traffic. The color represents the holiday, while the size of each circle represents the traffic volume on that holiday. The use of size and color in this way demonstrates relationships between numeric data and presents it in a compact format. 
![image](https://github.com/ZareClem/Minnesota_Interstate_Traffic_Volume_Dashboard/assets/138980152/4f89ff11-640f-4a8a-8a74-5036b730fad6)
