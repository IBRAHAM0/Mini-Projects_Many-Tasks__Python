# Los Angeles Crime Data Analysis

## Project Overview
This project analyzes crime data from Los Angeles, California, aiming to identify patterns in criminal behavior. Insights from this analysis support the Los Angeles Police Department (LAPD) in effectively allocating resources to enhance public safety across the city.

## Objectives
- Identify the hour with the highest frequency of crimes.
- Determine the area with the most frequent night crimes.
- Analyze crime distribution across different victim age groups.

## Tools & Techniques
- **Python Programming:** Data manipulation and analysis.
- **Pandas & NumPy:** Data cleaning and statistical analysis.
- **Seaborn:** Data visualization.

## Analysis Steps
1. **Data Preparation:**
   - Loaded crime data from `crimes.csv`.
   - Extracted and converted crime occurrence hours into integers.

2. **Peak Crime Hour Analysis:**
   - Identified the hour of the day with the highest crime frequency.

3. **Night Crimes Analysis:**
   - Filtered data for crimes occurring between 10 PM and 3:59 AM.
   - Identified the area with the highest frequency of night crimes.

4. **Victim Age Group Analysis:**
   - Categorized crimes based on victim age groups.
   - Calculated the frequency of crimes for each age group (0-17, 18-25, 26-34, 35-44, 45-54, 55-64, 65+).
   - Visualized age group distribution using seaborn.

## Insights
- **Peak Crime Hour:** Determined the time period with the highest crime rate, guiding resource scheduling.
- **Hotspot Areas:** Highlighted critical locations prone to night-time crimes for targeted police patrols.
- **Victim Demographics:** Provided a clear distribution of crime impact across age demographics.

## Conclusions
The analysis provides valuable insights to LAPD, helping optimize their resource deployment to reduce crime effectively and enhance community safety.

