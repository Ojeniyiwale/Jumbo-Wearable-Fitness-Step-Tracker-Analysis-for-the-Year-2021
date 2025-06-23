# Jumbo-Wearable-Fitness-Step-Tracker-Analysis-for-the-Year-2021  
This repository presents an analytical review of personal fitness metrics collected through a Jumbo wearable fitness tracker over the year 2021. It explores behavioral trends and wellness insights derived from data such as steps, distance, sleep hours, mood, water intake, and calories burned.

Project Structure

README.md - Project overview (this file)

data/ - Contains the anonymized and cleaned dataset (CSV format)

visualizations/ - Includes charts generated during analysis (PNG or JPG)

notebooks/ - Contains Excel dashboards and any Jupyter notebooks used

report/ - Final project report in Markdown and PDF format

Project Outline

Introduction

Story of Data

Data Splitting and Preprocessing

Pre-Analysis

In-Analysis

Post-Analysis and Insights

Data Visualizations & Charts

Recommendations and Observations

Conclusion

References & Appendices

Objective of the Project

To analyze fitness tracker metrics (steps, distance, sleep hours, mood, calories burned, active minutes, hydration) and assess trends, behavior changes, and overall health outcomes over a full calendar year.

Problem Statement

How effective is the user's fitness routine, and what habits or patterns support or hinder progress in wellness and physical activity?

Story of the Data

Source: Jumbo wearable tracker synced to fitness applications (e.g., Apple Health, Fitbit).

Data Type: Daily fitness logs for 2021.

Columns: date, steps, distance_km, sleep_hours, active_minutes, mood_score, water_intake_liters, calories_burned

Key Variables:

Steps & Distance – Measure of daily activity

Sleep Hours – Recovery and wellness

Mood Score – Subjective daily wellness input

Calories Burned – Output indicator

Hydration – Secondary wellness metric

Data Preprocessing

Removed incomplete/missing rows

Standardized distance to kilometers

Converted time formats

Created week/month aggregations using Excel formulas and pivot tables

Independent Variables:

Steps, active minutes, mood, water intake

Dependent Variables:

Calories burned, sleep hours, distance

Pre-Analysis Questions

What is the monthly trend in steps and calories burned?

How does mood influence physical activity?

Are sleep and active minutes inversely related?

Do weekends show higher or lower activity?

What is the hydration pattern and its effect?

In-Analysis Highlights

June saw peak values across all metrics (steps: 545,600; sleep: 389.6 hrs; calories: 16,368 kcal)

February had the lowest metrics (steps: 325,178; distance: 243.9 km; calories: 9,755 kcal)

Mood and Steps: Positive moods linked to increased distance

Sleep & Activity: Contrary to expectations, high activity did not reduce sleep

Weekday Trends: Mondays most active, Fridays least

Visualizations (in /visualizations folder)

Bar Chart: Steps per Month

Line Chart: Sleep Hours Over Time

Pie Chart: Mood and Distance Relation

Bar Graph: Active Minutes by Weekday

Key Recommendations

Introduce indoor workouts during low-activity months (Feb, Nov)

Schedule recovery and hydration tracking alongside activity logging

Use mood data to personalize workouts (e.g., stress relief exercises)

Run challenges in February and post-holiday months to maintain momentum

Conclusion

The analysis underscores the importance of routine, mood regulation, and seasonal variation in fitness performance. Regular review of fitness data leads to better goal setting, motivation, and holistic health improvements.

Limitations:

Mood and hydration were self-reported

Limited to a single user; findings are not generalizable

Future Enhancements:

Include heart rate, oxygen levels, and stress indicators

Benchmark data against similar users

Appendices

Monthly Pivot Tables (Excel)

Raw sanitized data sample (data/fitness_data_2021.csv)

Visuals (visualizations/ folder)

Formulas used in Excel dashboards

References

Microsoft Excel official documentation

Jumbo Wearable Tracker export guide

Author

[ojeniyi Wale] – Data Analyst & Fitness EnthusiastLinkedIn Profile | Medium | Portfolio Website
