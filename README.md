# UK-Road-Traffic-Accident-Analysis

<img width="570" height="373" alt="image" src="https://github.com/user-attachments/assets/58c40b04-2940-4ace-bc04-2cfde3a37141" />

##### • [Project Overview](#project-overview)
##### • [Business Problems](#business-problem)
##### • [Project Objectives](#project-objective)
##### • [Data Summary](#data-summary)
##### • [Skills and Technologies](#tools-and-skills)
##### • [Data Preprocessing](#data-preprocessing)
##### • [Key Insights](#key-insights)
##### • [Conclusion](#conclusion)

## Project Overview
End-to-end data analytics project focused on uncovering accident trends, severity patterns, environmental risk factors, and infrastructure insights from 307,972 UK road accident records from January 2021 to December 2022.
This project covers advanced Excel analytics including data cleaning, descriptive statistics, KPI development, an interactive Excel dashboard, and business-focused storytelling to support evidence-based road safety decisions.

## Business Problem
Road accidents remain a critical public safety concern in the UK. Despite the availability of large-scale government datasets, the data exists in unstructured formats that make it difficult for stakeholders — policymakers, traffic authorities, and urban planners — to extract actionable insights. 
This project addresses that challenge by transforming raw accident records into an interactive analytical solution to inform targeted safety interventions.

## Project Objectives
The primary objectives include:
• Clean and standardise the accident dataset
• Analyse the frequency and severity of road traffic accidents
• Identify key factors contributing to road traffic accidents
• Perform descriptive statistical analysis on the accident data
• Build an interactive Excel dashboard with dynamic slicers, KPI tiles, charts, and a geospatial heatmap of accident hotspots
• Provide actionable data-driven recommendations for policy, infrastructure, and public awareness

## Data Summary
Source: Provided by 10Alytics as part of training and research programme, comprising the UK Road Traffic Accident Records (2021-2022)
Size: 307,972 rows and 21 columns (numerical and categorical)
Key variables: Accident severity, speed limit, weather conditions, road surface conditions, light conditions, settlement area, number of casualties, junction control, coordinates, vehicle type

## Skills and Technologies
• Microsoft Excel - SUBSTITUTE(), TEXT(), XLOOKUP(), IFERROR()
• Pivot Tables
• Pivot Charts
• Descriptive Statistics
• Interactive Dashboarding - slicers, dynamic charts, KPI tiles, interactive filters
• Leadership and Cross-functional collaboration: led a 6-member analytics team to develop this deliver this project
• Stakeholder presentation delivery

#### Analytical Techniques

• KPI Development
• Trend Analysis
• Data Visualization
• Heat Map Analysis

## Data Preprocessing
The following extensive preprocessing was to the dataset to improve analytical quality and reporting consistency:
• Removed duplicate records
• Standardized date and year formats
• Replaced inconsistent text formatting
• Re-categorized variables into meaningful groups 
• Structured categorical variables for dashboard interaction

## Key Insights
#### Key Metrics
• Total Accidents: 307,972
• Total Casualties: 417,882
• Fatal Injuries: 3,953
• Serious Injuries: 40,740
• Slight Injuries: 263,279
• Vehicles Involved: 563,301

#### Descriptive statistics
Variable             Mean    Median   Std Dev   Range   Skewness
─────────────────────────────────────────────────────────────────
No. of casualties    1.36    1        0.82      47      5.69
Speed limit (mph)   38.87   30       14.03      60      1.14

• Casualty distribution showed strong right skewness, with most accidents involving a single casualty (mean casualties)  — a small number of high-impact events inflate the mean significantly. Speed limit clusters around 30 mph (mean speed 38.87) with a long tail toward higher limits

#### Temporal Patterns
• Accident frequency peaked during afternoons and evenings, 4 pm–8 pm being the most dangerous time band
• Friday recorded the highest daily volume, driven by end-of-week traffic surges
• Accident frequency peaked in October–November, consistent with reduced daylight and worsening weather

#### Speed and accident severity
• Higher speed roads (50–70 mph) showed stronger associations with serious and fatal injuries
• 30 mph zones accounted for the highest total volume (~200,000+), reflecting dense urban traffic concentration

#### Environmental Conditions
Urban settlements (64%) recorded substantially more accidents than rural regions (36%) even though rural was generally more severe
Most accidents occurred on dry roads; however, adverse weather and poor lighting conditions significantly increased accident severity risk

## Actionable Recommendations
#### Policy measures
• Enforce 30 mph speed management in urban and residential areas with cameras and speed bumps
• Introduce stiffer penalties for repeat traffic offenders
• Deploy additional traffic patrol officers in November, the peak accident month

#### Infrastructure Improvements
Improve junction visibility and signage
Improve night-time street lighting along darkness hotspot corridors
Increase snowplow capacity in rural areas for winter conditions
Deploy smart traffic signals and automated control at peak-hour bottlenecks
Expand pedestrian and cycling infrastructure in urban accident clusters

#### Public Awareness
Launch campaigns targeting speed awareness in 50–70 mph zones, wet-weather driving, and night-time risk
Implement school-zone safety programmes in high-density urban accident clusters
Run seasonal campaigns ahead of the October–November high-risk period

## Conclusions
The analysis revealed clear patterns in UK road accidents, showing that factors such as speed limits, weather conditions, lighting, and road surface conditions significantly influence accident severity.
While most accidents resulted in slight injuries, high-speed roads and adverse environmental conditions were strongly associated with serious and fatal outcomes. 
The project demonstrates how data analytics and interactive reporting can transform raw transportation data into actionable insights that support safer roads, improved infrastructure planning, and evidence-based policy decisions.
