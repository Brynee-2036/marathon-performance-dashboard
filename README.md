# marathon-performance-dashboard
🏃 Marathon Performance Dashboard
A Power BI, Python, and Tableau analytics project using Garmin marathon training data.
________________________________________
Project Overview
This project analyzes marathon training data exported from Garmin to monitor training performance, identify trends, and support data-driven coaching decisions. The dashboard combines data visualization and analytics techniques to provide insights into endurance, consistency, and overall race readiness.
________________________________________
Objective
The goal of this project is to build an executive-style performance dashboard that answers questions such as:
•	Am I increasing my weekly mileage safely?
•	Is my pace improving over time?
•	Am I following my Garmin marathon training plan consistently?
•	How is my heart rate changing as my fitness improves?
•	Am I ready for race day?
This project also demonstrates practical skills in Python, Power BI, Tableau, GitHub, and data storytelling.
________________________________________
Dataset
Source: Garmin Connect
Data includes:
•	Running date
•	Distance
•	Duration
•	Average pace
•	Moving time
•	Elevation gain
•	Average cadence
•	Average heart rate
•	Maximum heart rate
•	Calories burned
•	Training type (easy run, intervals, long run, etc.)
Future versions may incorporate:
•	Sleep data
•	Training readiness
•	Recovery time
•	Weather conditions
•	Race results
________________________________________
Dashboard Preview
(Add screenshots after you've built the dashboard.)
Executive KPIs
•	Weekly Mileage
•	Average Pace
•	Long Run Distance
•	Running Frequency
•	Heart Rate Trends
•	Elevation Gain
•	Cadence
•	Time in Heart Rate Zones
•	Training Consistency %
•	Total Training Hours
Dashboard Pages
1.	Executive Summary
2.	Training Volume
3.	Pace Analysis
4.	Heart Rate Analytics
5.	Training Consistency
6.	Race Readiness
________________________________________
Tools Used
Tool	Purpose
Power BI	Dashboard development
Python	Data cleaning and analysis
Pandas	Data transformation
GitHub	Version control and portfolio
Tableau	Data visualization
Garmin Connect	Data source
Excel	Data validation and exploration
________________________________________
Key Skills Demonstrated
•	Data Cleaning
•	Data Modeling
•	Data Visualization
•	Dashboard Design
•	KPI Development
•	Data Storytelling
•	Python Programming
•	Power BI
•	Tableau
•	Git Version Control
________________________________________
Lessons Learned
Use this section to reflect on what you learned during the project. For example:
•	Built an end-to-end analytics workflow from raw data to executive dashboard.
•	Improved skills in importing and transforming fitness data.
•	Learned to design KPIs that align with business-style reporting.
•	Practiced creating dashboards that communicate insights rather than just displaying charts.
•	Strengthened GitHub documentation and portfolio presentation skills.
________________________________________
Future Enhancements
•	Integrate Garmin API for automated data refresh.
•	Add marathon finish time prediction using machine learning.
•	Include HYROX training metrics alongside marathon data.
•	Compare current training cycle with previous cycles.
•	Add weather and terrain analysis.
•	Create an AI-generated weekly training summary.
________________________________________
About the Author
Brynee Dade
Senior Consultant transitioning into AI & Data with a focus on analytics, visualization, and machine learning. This project is part of a larger portfolio documenting my journey toward becoming an AI & Data consultant.

_________________________________________
KPI Definitions
KPI	              Definition	                       Calculation	                                   Why It Matters
Weekly Mileage	Total distance completed each week.	Sum of all run distances (miles) by week.	Tracks training volume and progression toward marathon readiness.
Average Pace	Average pace across all runs during the selected period.	Total moving time ÷ Total distance.	Measures overall running efficiency and fitness improvements.
Long Run Distance	Longest single run completed during the week.	Maximum distance from a single activity.	Indicates progress toward marathon endurance goals.
Running Frequency	Number of completed runs per week.	Count of running activities.	Measures adherence to the training plan and consistency.
Heart Rate Trends	Average and maximum heart rate over time.	Average/Max HR by run or week.	Evaluates cardiovascular adaptation and training intensity.
Elevation Gain	Total elevation climbed during runs.	Sum of elevation gain (feet or meters).	Helps explain pace differences and training difficulty.
Cadence	Average running cadence.	Average steps per minute across runs.	Used to monitor running efficiency and form.
Time in Heart Rate Zones	Time spent in each heart rate training zone.	Total minutes per HR zone (Zones 1–5).	Confirms workouts match the intended training intensity.
Training Consistency %	Percentage of planned runs that were completed.	(Completed Runs ÷ Planned Runs) × 100	Measures adherence to the Garmin training plan.
Total Training Hours	Total time spent running during the selected period.	Sum of moving time.	Reflects overall training load and complements mileage.
________________________________________
📊 Dashboard Layout
Top KPI Cards
•	Weekly Mileage
•	Average Pace
•	Long Run Distance
•	Running Frequency
•	Training Consistency %
•	Total Training Hours
________________________________________
Trend Visuals
•	Weekly Mileage Trend (Line Chart)
•	Average Pace Trend (Line Chart)
•	Heart Rate Trend (Line Chart)
•	Elevation Gain by Run (Column Chart)
•	Long Run Progression (Line Chart)
________________________________________
Training Quality
•	Time in Heart Rate Zones (Stacked Bar or Donut Chart)
•	Average Cadence by Week (Line Chart)
•	Pace vs. Heart Rate (Scatter Plot)
________________________________________
Calendar & Consistency
•	Training Calendar Heat Map
•	Planned vs. Completed Runs
•	Running Days by Week
________________________________________
📈 Executive Insights
Include a small panel with automatically generated or manually written observations, such as:
•	Weekly mileage increased by 12% compared to the previous week.
•	Average pace improved by 18 seconds per mile.
•	Training consistency remained above 95%.
•	Most training time was spent in Zone 2, aligning with the marathon base-building phase.
•	Long run distance increased from 8 to 10 miles, supporting endurance progression.
________________________________________
🚀 Stretch KPIs (to make your portfolio stand out)
Since you're using Garmin and training for both a HYROX doubles event and a marathon, you can add more advanced metrics later:
KPI	Why Include It
Training Load	Shows cumulative workload and recovery balance.
Acute:Chronic Workload Ratio	Demonstrates understanding of injury-risk monitoring.
VO₂ Max Trend	Tracks aerobic fitness improvements.
Recovery Time	Uses Garmin recovery recommendations to monitor readiness.
Average Sleep Score	Correlates sleep quality with training performance.
Resting Heart Rate	Indicates fitness and recovery trends.
Training Readiness	Garmin metric that combines recovery factors.
Race Pace Progress	Compares current pace with marathon goal pace.
Predicted Marathon Finish Time	Tracks expected race performance over time.
HYROX Readiness Score	A custom metric combining running, strength sessions, and consistency.
These additional metrics make the dashboard more unique because they move beyond simple reporting into performance analytics, which aligns well with your AI & Data career goals and demonstrates more advanced analytical thinking. cite
This is actually one of the most important parts of an analytics portfolio. A README.md (pronounced "read me") is the first page someone sees when they open your GitHub project. Think of it as the executive summary of your work.
If a Deloitte manager, recruiter, or UT Austin admissions reviewer visits your GitHub, they should be able to understand your project in under two minutes.
For your Marathon Performance Dashboard, I'd structure it like this:
________________________________________
