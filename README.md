# Skyline Air: On-Time Performance Analysis
<img width="1207" height="256" alt="image" src="https://github.com/user-attachments/assets/e299fce5-fe7e-428e-8016-fe64a46a5b26" />

## Table of Contents

1. [Project Overview](#project-overview)
2. [Business Problem](#business-problem)
3. [Project Objectives](#project-objectives)
4. [Dataset Overview](#dataset-overview)
5. [Tools and Techniques](#tools-and-techniques)
6. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
7. [Methodology](#methodology)
8. [Key Business Questions](#key-business-questions)
9. [Analysis and Key Findings](#analysis-and-key-findings)
10. [Business Insights](#business-insights)
11. [Recommendations](#recommendations)
12. [Dashboard Preview](#dashboard-preview)
13. [Project Files](#project-files)
14. [Limitations](#limitations)
15. [Conclusion](#conclusion)

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

## Dataset Overview

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

## Tools and Techniques

- Microsoft Excel
- Excel Formulas and Functions
- Excel Tables
- Power Pivot / Data Model
- PivotTables
- Pivot Charts
- Interactive Dashboard

## Key Business Questions

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

## Methodology

The analysis used a 15-minute departure tolerance.

A flight was classified as:

- **On Time:** Departed no more than 15 minutes after its scheduled time.
- **Delayed:** Departed 16 minutes or more after its scheduled time.
- **Cancelled:** Flight status was recorded as cancelled.

Performance was evaluated using verified departure-delay values.

The analysis included monthly trends, airport comparisons, weekday performance, time-of-day analysis, aircraft performance and delay-cause analysis.

## Analysis and Key Findings

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

## Limitations

Although the data was cleaned and validated, some limitations remained and should be considered when interpreting the findings.

1. **Missing Actual Departure Times:** 22 completed flights had no actual departure time. These flights were classified as delayed by the workbook formula, which may have understated the reported on-time performance. The reported OTP remains 73.03% to stay consistent with the submitted workbook. Based on the originally recorded delays, the adjusted OTP would be approximately 74.9%.

2. **Missing Delay Causes:** 143 delay-cause fields were blank. This limited the ability to identify the recorded reasons behind every flight's performance.

3. **Missing Arrival Delay Information:** Arrival delay data was unavailable for 43 flights. Therefore, the analysis focused on departure performance rather than arrival on-time performance.

4. **Limited Dataset Period:** The analysis covered one year and approximately 1,000 flights. Some airports had relatively small flight counts, meaning a few flights could noticeably affect their delay rates.

5. **Inconsistent Labels:** Some airport codes and delay-cause labels still contained differences in capitalisation or trailing spaces. These did not change the reported PivotTable results but should be standardised before future analysis.

6. **Correlation Does Not Prove Causation:** Differences in delay rates across aircraft types and other categories show associations, not necessarily direct causes.

7. **Dashboard Accuracy:** Two dashboard charts (Delay Rate by Origin and Monthly OTP Trend) did not match their corresponding PivotTable results. The Cleaning_Log management priorities table also contained incorrect entries. The report's findings were based on the correct PivotTable figures, and these workbook items should be corrected before the dashboard is used for management decisions.

Despite these limitations, the project provides useful insights into Skyline Air's departure performance and highlights areas where operational improvements and better data collection are needed.

## Conclusion

The project demonstrates how Microsoft Excel can be used to clean operational data, analyse business performance, develop dashboards and generate actionable insights.

The findings show that Skyline Air's operational challenges are concentrated around specific airports, departure periods and delay causes.

The recommendations provide management with areas to investigate and monitor to improve flight punctuality.

**Project Type:** Excel Data Analytics / Business Analytics

**Industry:** Aviation and Airline Operations

**Tool:** Microsoft Excel
