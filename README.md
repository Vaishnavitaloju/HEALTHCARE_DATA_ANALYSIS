# HEALTHCARE DATA ANALYSIS AND BUSINESS INTELLIGENCE DASHBOARD

# Project Overview

This project focuses on analyzing healthcare data to derive meaningful insights on patient visits, wait times, and satisfaction scores. The interactive visualizations presented in this Power BI dashboard make it easier for health care administrators to understand the trend and thus improve service efficiencies.

# Key metrics and insights include:

Total Visits: 9,216

Gender Distribution: 4,705 Males, 4,487 Females

Visit Timing: 6,574 on weekdays, 2,642 on weekends

Average Wait Time: 35 minutes

Average Satisfaction Score: 5 / 10

# Dashboard Features

1. Daily Visits

Helps in visualizing the number of patient visits per day of the month, so that peak and low visit days can be identified.

2. Monthly Visits

This shows the distribution of patient visits by each month, indicating trends and patterns. August showed the highest number of patient visits (1,024), while February showed the least (431).

3. Yearly and Quarterly Visits

Yearly Visits: Comparison of visits between 2019 and 2020.

Quarterly Visits: Emphasizes the total visits during each quarter of the year, with the highest volume in the fourth quarter.

4. Day of Week Analysis

Reveals which days of the week have the most footfall. Monday is the most busy day, with 1,377 patients, and Friday is the least busy, with 1,260 patients.

5. Wait Time Distribution

Helps to break down patient wait times into intervals. Such analysis identifies bottlenecks in the service delivery process.

6. Moment Distribution

Figures out the proportion of visits among AM and PM hours of a day to identify peak hours. AM comprises 49.74%, and PM comprises 50.26%.

# Data Fields

The dataset includes the following fields:

| Field Name          | Description                                        |
| ------------------- | -------------------------------------------------- |
| Total Visits        | Total number of patient visits                     |
| Males / Females     | Gender distribution of patients                    |
| Weekdays / Weekends | Count of visits on weekdays and weekends           |
| Avg Wait Time       | Average patient waiting time in minutes            |
| patient_sat_score   | Patient satisfaction score                         |
| patient_age         | Age of patients                                    |
| patient_gender      | Gender of patients                                 |
| patient_id          | Unique ID of each patient                          |
| patient_race        | Patient race                                       |
| VisitDayType        | AM or PM visit                                     |
| WaitTimeclub        | Wait time intervals (10–20 mins, 21–30 mins, etc.) |
| department_referral | Department referral information                    |


# Technologies Used

Power BI – For Data Visualization and Dashboard Creation

DAX: Calculated metrics like average wait time and satisfaction score

Excel / CSV: Source data storage and preparation

# Insights & Recommendations

Mondays and Saturdays are the busiest days, indicating that extra staff may be required on these days.

Average wait time 35 mins suggests potential delay in service, which might affect patient satisfaction.

Satisfaction score: 5/10 - It indicates that the process needs to be improved.

The almost equal distribution of AM and PM visits points to the consistency of demand.
