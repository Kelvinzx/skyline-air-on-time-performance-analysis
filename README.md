# Skyline Air: On-Time Performance Analysis
<img width="1207" height="256" alt="image" src="https://github.com/user-attachments/assets/e299fce5-fe7e-428e-8016-fe64a46a5b26" />



## Project Overview

This project analyses one year of flight operational data for Skyline Air, a fictional domestic airline in the United States.

The project was completed using Microsoft Excel to investigate flight delays, evaluate on-time performance, identify operational challenges and provide recommendations that can help management improve airline operations.

The analysis covers September 2025 to August 2026 and focuses on identifying when, where and why flights experience delays.

## Business Problem

Skyline Air has experienced a decline in on-time flight performance and an increase in customer complaints.

Management needs a clear understanding of the factors contributing to flight delays and the areas requiring immediate attention.

This project uses data analysis to identify operational weaknesses and provide evidence-based recommendations.

## Project Objectives

- Evaluate the airline's overall on-time performance.
- Identify monthly flight performance trends.
- Determine which departure airports experience the highest delay rates.
- Analyse flight delays by day and time of departure.
- Compare operational performance across aircraft types.
- Identify the most common causes of flight delays.
- Recommend practical improvements to airline operations.

## Dataset Description

The project contains 1,012 raw flight records, which were reduced to 1,000 unique flight records after cleaning.

**Coverage:** 1 September 2025 – 31 August 2026.

The dataset includes information such as:

- Flight ID and flight number
- Flight date
- Origin and destination airports
- Aircraft type
- Scheduled departure
- Actual departure
- Departure delay
- Arrival delay
- Delay cause
- Flight status
- Distance travelled

## Tools and Technologies

- Microsoft Excel
- Excel Formulas and Functions
- Excel Tables
- Power Pivot / Data Model
- PivotTables
- Pivot Charts
- Interactive Dashboard

## Business Questions

The analysis investigated the following questions:

1. What is Skyline Air's overall on-time performance?
2. How does flight performance vary by month?
3. Which airports experience the highest flight delay rates?
4. Which days of the week have the highest delay risk?
5. Which times of the day experience the most delays?
6. Are certain aircraft types associated with higher delay rates?
7. What are the most common causes of flight delays?
8. Which delay factors are within the airline's operational control?

## Data Cleaning and Preparation

The raw dataset was reviewed and prepared before analysis.

Key activities included:

- Removing 12 duplicate records.
- Standardising airport names and codes.
- Standardising delay-cause categories.
- Identifying missing values.
- Recalculating departure delays using scheduled and actual departure times.
- Correcting six inaccurate departure-delay values.
- Identifying invalid distance values.
- Creating calculated columns for analysis.

The original raw dataset was preserved separately from the cleaned dataset.

## Analysis Methodology

The analysis used a 15-minute departure tolerance.

A flight was classified as:

- **On Time:** Departed no more than 15 minutes after its scheduled time.
- **Delayed:** Departed 16 minutes or more after its scheduled time.
- **Cancelled:** Flight status was recorded as cancelled.

Performance was evaluated using verified departure-delay values.

The analysis included monthly trends, airport comparisons, weekday performance, time-of-day analysis, aircraft performance and delay-cause analysis.

## Key Findings

The analysis produced the following results:

| KPI | Result |
|---|---:|
| Total Flights | 1,000 |
| Completed Flights | 979 |
| Cancelled Flights | 21 |
| On-Time Flights | 715 |
| Delayed Flights | 264 |
| On-Time Performance | 73.03% |
| Delay Rate | 26.97% |
| Cancellation Rate | 2.1% |

Additional findings:

- On-time performance declined by 8.3 percentage points between September–February and March–August.
- Seattle recorded the highest delay rate at 36.5%.
- Atlanta recorded a 32.7% delay rate and the highest number of delayed flights (52).
- Evening departures recorded a 32.5% delay rate.
- Sunday recorded the highest weekday delay rate at 31.5%.
- Late Aircraft and Carrier issues accounted for 155 of the 246 delays with recorded causes.

## Business Insights

The analysis suggests that flight delays are a greater operational challenge than cancellations.

Performance also varies across airports, departure times and months.

Late aircraft and carrier-related issues represent important areas for management attention because they account for a substantial share of delays with known causes.

The analysis also highlights the importance of improving aircraft turnaround processes and operational planning during peak periods.

## Recommendations

Based on the findings, the report recommends:

1. Improve aircraft turnaround processes to reduce delays carried over from earlier flights.
2. Review carrier-related processes, including crew scheduling, boarding and maintenance readiness.
3. Prioritise operational reviews at Atlanta and Seattle airports.
4. Improve staffing and scheduling during evening and peak travel periods.
5. Introduce proactive passenger delay notifications.
6. Improve data completeness by recording actual departure times and delay causes consistently.
7. Monitor performance through regular dashboard updates.

## Dashboard Preview

The interactive Excel dashboard provides an overview of Skyline Air's flight performance, highlighting key performance indicators and operational trends.

<img width="1204" height="705" alt="image" src="https://github.com/user-attachments/assets/2f56f3aa-63b7-422a-bffb-5d98c99075df" />

### Monthly On-Time Performance Trend

This chart shows how Skyline Air's on-time performance changed across the 12-month analysis period.
<img width="598" height="357" alt="image" src="https://github.com/user-attachments/assets/b3cb63f9-6fe6-45c7-8305-99a41c01880a" />

### Flight Delay Cause Analysis

This chart highlights the recorded causes of flight delays and helps identify the operational areas requiring management attention.

<img width="420" height="440" alt="image" src="https://github.com/user-attachments/assets/ef36a53d-58e7-4d87-8b15-037d96204be7" />


## Project Files

| File | Description |
|---|---|
| [Excel Workbook](https://github.com/Kelvinzx/skyline-air-on-time-performance-analysis/blob/main/Skyline_Air_Flight_Data.xlsx) | Contains the raw data, cleaned data, analysis and dashboard |
| [Project Report](https://github.com/Kelvinzx/skyline-air-on-time-performance-analysis/blob/main/Skyline_Air_Final_Presentation%20(1).pptx) | Documents the business problem, methodology, findings, insights and recommendations |
| Screenshots | Visual previews of the Excel dashboard and selected analysis charts |

## Conclusion

The project demonstrates how Microsoft Excel can be used to clean operational data, analyse business performance, develop dashboards and generate actionable insights.

The findings show that Skyline Air's operational challenges are concentrated around specific airports, departure periods and delay causes.

The recommendations provide management with areas to investigate and monitor to improve flight punctuality.

**Project Type:** Excel Data Analytics / Business Analytics

**Industry:** Aviation and Airline Operations

**Tool:** Microsoft Excel
