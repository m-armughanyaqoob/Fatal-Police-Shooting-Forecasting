# Fatal Police Shooting Forecast

This project analyzes and forecasts fatal police shootings in the United States using a dataset compiled by The Washington Post. The dataset records every fatal shooting by a police officer since 2015, with a focus on incidents similar to the Michael Brown case. The dataset includes various factors such as the victim's race, the circumstances of the shooting, whether the victim was armed or experiencing a mental health crisis, and more.

## Dataset Overview

The dataset contains the following columns:
- **Id:** Unique identifier for each incident
- **Name:** Name of the victim
- **Date:** Date of the incident
- **Manner_of_death:** Circumstances of the death
- **Armed:** Indicates if the victim was armed
- **Age:** Age of the victim
- **Gender:** Gender of the victim
- **Race:** Race of the victim
- **City, State:** Location of the incident
- **Signs_of_mental_illness:** Indicates if the victim was experiencing a mental health crisis
- **Threat_level:** The perceived threat level during the incident
- **Flee:** Indicates if the victim attempted to flee
- **Body_camera:** Indicates if a body camera was in use during the incident
- **Longitude, Latitude:** Geographical coordinates of the incident
- **Is_geocoding_exact:** Indicates if the geocoding data is exact

## Key Findings

1. **Trends Over Time:**
   - The highest number of incidents occurred in 2018, mid-2020, and mid-2021.
   - There were notable decreases in incidents at the end of 2018 and 2020.
   - The predicted trend for 2023 and 2024 indicates a slight decrease in fatal police shootings.

2. **Demographic Impact:**
   - The majority of victims were from Black, Hispanic, and White communities.
   - White individuals were the most commonly targeted racial group, followed by Black and Hispanic individuals.
   - An interesting observation is that victims from the Black community were involved in around half of the incidents where the victims were White.

3. **Age Distribution:**
   - The age group most frequently affected by fatal police shootings was between 32 and 36 years old.
   - Individuals over 80 years old and those under 20 years old were the least affected age groups.

4. **Geographical Hotspots:**
   - California and Texas were identified as the main hotspots for these incidents.
   - Rhode Island had the fewest incidents among all states.

5. **Incident Characteristics:**
   - Most incidents involved a direct threat from the individual towards the police, often resulting in an attack.

## Project Files

The following files are included in this repository:
1. **Police Shooting Forecasting.ipynb**  
   This Jupyter Notebook contains the code used to analyze the dataset and build the forecasting models.
   
2. **Forecasting Results.pdf**  
   This PDF document presents the results of the forecasting analysis, including visualizations and key insights.

## Conclusion

Based on the data from The Washington Post, the analysis and forecasting of fatal police shootings reveal important trends and patterns. The findings suggest a slight decrease in the number of shootings in 2023 and 2024, with a significant focus on the impact on specific racial groups and age distributions. This analysis provides valuable insights into the ongoing issue of fatal police shootings in the United States.
