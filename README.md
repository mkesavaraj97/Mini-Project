🚦 Traffic Accident Analysis Dashboard using Excel & Power BI

📌 Project Overview

This project presents an interactive Traffic Accident Analysis Dashboard developed using Microsoft Excel and Microsoft Power BI. The objective is to analyze traffic accident data across various states and cities in India, helping identify accident-prone locations, compare accident categories, and evaluate injury and fatality statistics.
The dashboard provides meaningful insights through KPI cards, interactive charts, slicers, and DAX calculations, enabling data-driven decision-making for traffic safety and public policy.
________________________________________

🎯 Project Objectives

•	Analyze total traffic accident cases across different locations.
•	Compare Road, Railway, and Railway Crossing accidents.
•	Identify high-risk states and cities.
•	Evaluate total injuries and fatalities.
•	Analyze injury and death rates.
•	Create an interactive dashboard for effective decision-making.
________________________________________

🛠️ Tools & Technologies

•	Microsoft Excel – Data Cleaning & Preparation
•	Power Query – Data Transformation
•	Microsoft Power BI – Dashboard Development
•	DAX (Data Analysis Expressions) – Measures & Calculations
________________________________________

📊 Dataset Information

Domain: Transportation Analytics (Traffic Safety)
The dataset contains traffic accident statistics for various States, Union Territories, and Cities.
Dataset Features
•	Location
•	Location Type
•	Road Cases
•	Road Injured
•	Road Deaths
•	Railway Cases
•	Railway Injured
•	Railway Deaths
•	Railway Crossing Cases
•	Railway Crossing Injured
•	Railway Crossing Deaths
•	Total Traffic Cases
•	Total Traffic Injured
•	Total Traffic Deaths
•	Injury Rate
•	Death Rate
________________________________________

🧹 Data Cleaning

•	Imported the dataset into Excel.
•	Removed duplicate records.
•	Verified data types.
•	Handled missing values.
•	Renamed columns for consistency.
•	Formatted percentage columns.
•	Converted the dataset into an Excel Table.
________________________________________

🔄 Data Transformation (Power Query)

•	Imported the dataset into Power BI.
•	Verified column data types.
•	Removed unnecessary data.
•	Checked for null values.
•	Renamed columns where required.
•	Applied data formatting.
•	Loaded the cleaned dataset into the Power BI model.
________________________________________

📐 Data Modeling

•	Imported a single fact table (Traffic_Data) into Power BI.
•	Verified data types for all columns.
•	Formatted percentage fields.
•	Optimized the model for reporting and DAX calculations.
________________________________________
📏 DAX Measures
Total Cases =
SUM('Traffic_Data'[Total Traffic Cases])

Total Injured =
SUM('Traffic_Data'[Total Traffic Injured])

Total Deaths =
SUM('Traffic_Data'[Total Traffic Deaths])

Death Rate =
DIVIDE([Total Deaths],[Total Cases])

Injury Rate =
DIVIDE([Total Injured],[Total Cases])
________________________________________
📈 Dashboard Features
•	📌 KPI Cards
•	📊 Bar Chart
•	📉 Line Chart
•	🍩 Donut Chart
•	🌳 Treemap
•	📋 Column Chart
•	🎛️ Interactive Slicers
•	🔄 Cross Filtering
•	📍 Location-wise Analysis
•	🚦 Accident Category Comparison
________________________________________

📊 Dashboard KPIs
•	🚗 Total Accident Cases
•	🤕 Total Injured
•	⚫ Total Deaths
•	📈 Death Rate
________________________________________

📷 Dashboard Preview

 ________________________________________
📌 Key Insights
📍 Descriptive
The dashboard summarizes total accident cases, injuries, deaths, and death rate, providing a clear overview of traffic accident statistics.


🔍 Diagnostic
High accident cases and death rates identify accident-prone locations that require further investigation and safety improvements.
📈 Predictive
Historical accident trends indicate that locations with consistently high accident cases may continue to remain high-risk areas.
✅ Prescriptive
The dashboard supports data-driven decisions by helping authorities prioritize road safety measures, improve emergency response, and reduce accident-related fatalities.
________________________________________
💼 Business Value
This dashboard can help:
•	Government Departments
•	Traffic Police
•	Transport Authorities
•	Public Safety Organizations
•	Urban Planners
•	Data Analysts & Researchers
________________________________________
🚀 Skills Demonstrated
•	Microsoft Excel
•	Power Query
•	Power BI
•	Data Cleaning
•	Data Transformation
•	Data Modeling
•	DAX
•	KPI Design
•	Data Visualization
•	Dashboard Development
•	Business Intelligence
•	Analytical Thinking
________________________________________
📂 Project Structure
Traffic-Accident-Analysis/
│
├── Dataset/
│   └── Traffic_Accidents.xlsx
│
├── PowerBI/
│   └── Traffic_Accident_Dashboard.pbix
│
├── Images/
│   └── Traffic_Accident_Dashboard.png
│
├── Documentation/
│   └── Project_Documentation.pdf
│
└── README.md
________________________________________
🎯 Conclusion
The Traffic Accident Analysis Dashboard demonstrates how Excel and Power BI can transform raw accident data into meaningful insights through data cleaning, DAX calculations, and interactive visualizations. The dashboard enables users to monitor accident trends, compare accident categories, identify high-risk locations, and support data-driven decisions for improving road safety.
________________________________________
👨💻 Author
Kesavaraj M
Aspiring Data Analyst
Skills: Excel | Power BI | DAX | Data Visualization | Data Analytics


