# Electricity-consumption-analysis-school
Data analysis of daily electricity consumption in a school building using Python

Project Objective

This project aims to analyze the daily electricity consumption of a school to:

Understand the factors influencing energy consumption,

Identify energy-intensive periods,

Highlight the impact of temperature and school schedule,

Provide actionable insights for building energy management.

This project falls under the scope of Data Analysis applied to energy management.

🗂️ Dataset Description

The dataset used is a dataset representing one full year of operation of a school.

Main Variables:

date: the date of the observation

temperature_C: daily average outdoor temperature (°C)

electricity_kWh: daily electricity consumption (kWh)

school_open: indicates whether the school was open (1 = school day, 0 = weekend/holiday)

An additional variable created during analysis:

season: Winter, Spring, Summer, Autumn

🛠️ Tools Used

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook (Anaconda)

🔎 Analysis Methodology

The analysis was performed in several stages:

1️⃣ Descriptive Statistics

Key metrics: mean, minimum, maximum, median

Outlier detection (using the IQR method)

2️⃣ Time-Based and Seasonal Analysis

Dividing the year into seasons

Comparing average consumption across seasons

Highlighting the energy seasonality

3️⃣ Temperature vs Consumption Analysis

Scatter plot of temperature vs electricity consumption

Adding a trend line (linear regression)

Investigating the relationship between temperature decrease and consumption increase

4️⃣ Weekday vs Weekend Consumption

Comparing consumption between school days and weekends

Checking the persistence of the temperature-consumption relationship

📈 Key Findings

Electricity consumption follows a strong seasonal pattern

It is minimal in the summer (~111.45 kWh/day on average)

It is maximal in the winter (~224.55 kWh/day on average)

The consumption varies by a factor of two between summer and winter

A negative relationship is observed between outdoor temperature and electricity consumption

This relationship holds true both on weekdays and weekends

These findings confirm that electric heating is the primary energy consumption driver for both classrooms and administrative offices.

💡 Energy Optimization Recommendations

Based on the analysis, several optimization opportunities are identified:

Lowering heating settings during weekends and holidays

Improving thermal regulation during winter months

Monitoring days with unusually high consumption

Implementing daily energy consumption tracking indicators

🚀 Improvement Opportunities

This project could be enhanced by:

Adding gas or district heating consumption data

Including holiday schedules in the dataset

Creating a short-term consumption forecasting model

Building an interactive dashboard (Power BI / Tableau)

👤 Author

This project was completed by a building energy engineer transitioning to the role of a Data Analyst, with a focus on energy data analysis.
