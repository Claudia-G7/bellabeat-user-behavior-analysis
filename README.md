# Bellabeat Smart Device — User Behavior Analysis
**Google Data Analytics Capstone | Tools: Google Sheets**

## Overview
Analysis of FitBit usage data (35 users, March–April 2016) to identify behavioral 
patterns and engagement opportunities for Bellabeat's product strategy.

**Business question:** How can Bellabeat use smart device usage data to inform 
decisions that improve user engagement and product positioning?

---

## Data sources & preparation
- **Dataset:** [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) 
  (Kaggle, Möbius — CC0 Public Domain)
- Selected datasets: `daily_activity` and `minute_sleep` (most relevant for behavioral analysis)
- Date fields standardised; day of week extracted for temporal analysis
- Sleep data aggregated from minute-level to daily-level
- **Exclusions applied:**
  - Users with fewer than 10 days of sleep data (incomplete records)
  - Users with 0 steps but non-zero calorie burn (likely device malfunction)

> Limitations acknowledged: small sample (35 users), 2-month window, no demographic 
> data available. Findings are exploratory and not statistically representative.

---

## Key findings

### 1. Activity tracking is used consistently — sleep tracking is not
Daily step tracking was the most consistently used feature across users. 
Sleep data showed significantly lower and more irregular adoption, suggesting 
users perceive the device primarily as a fitness tool rather than a holistic 
health monitor.

### 2. Weekly activity dips are predictable
Lower physical activity was consistently observed on **Tuesdays and Sundays**, 
with peaks on Mondays and Wednesdays.

> These predictable dips represent clear opportunities for targeted engagement 
> strategies (reminders, challenges) on low-motivation days.

### 3. Most users are moderately active — not highly active
User segmentation by average daily steps revealed that the largest group falls 
into the **moderately active** category, followed by sedentary users. 
Highly active users represent the smallest proportion.

> This distribution suggests the device is used for general wellness, not 
> performance tracking — with room to nudge users toward gradual improvement.

### 4. Activity level does not predict sleep stage distribution
No meaningful differences in light sleep, deep sleep, or REM were found across 
sedentary, moderate, and active user profiles.

> This challenges a common assumption and may reflect the known limitations of 
> wrist-based REM detection (indirect measurement via movement + heart rate). 
> Result should be interpreted with caution given sample size.

---

## Recommendations

| # | Recommendation | Based on |
|---|---------------|----------|
| 1 | Increase sleep feature adoption via in-app prompts and educational content | Finding 1 |
| 2 | Trigger personalised notifications on Tuesdays and Sundays | Finding 2 |
| 3 | Design habit-building messaging for the moderately active segment | Finding 3 |

---

## Skills demonstrated
`Data cleaning` `Outlier detection` `Data aggregation` `Pivot tables` 
`User segmentation` `Exploratory data analysis` `Business recommendations`

---

*Part of my transition into health data analytics — combining a life sciences 
background with data analysis skills applied to the wellness and pharma sector.*
