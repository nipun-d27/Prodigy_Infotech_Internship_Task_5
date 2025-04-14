# Prodigy_Infotech_Internship_Task_5
Analyzing and Visualizing traffic accident data to identify patterns related to road conditions, weather, time of day, accident hotspots and contributing factors.

**Traffic Accident Causes and Factors Analysis:** This project involves analyzing a traffic accident dataset as part of a data science task. The analysis aims to uncover insights into accident patterns based on time, location, and environmental conditions.

**Dataset and Preparation:**
Imported two datasets: a cleaned dataset and the original RTA dataset.
Merged the following columns from the RTA dataset into the cleaned dataset:
Time
Day_of_week
Area_accident_occured
Road_surface_conditions

Performed basic exploratory data analysis (EDA) on the merged dataset.

**Visualizations Created:**
**Number of Accidents by Hour of Day**
A countplot showing the distribution of accidents across different hours.

**Number of Accidents by Day of the Week**
A countplot to observe which weekdays see the most accidents.

**Accident Severity by Hour of Day**
A countplot categorized by severity levels to analyze severity trends over the day.

**Top 10 Accident Causes by Day of the Week**
A countplot showing how the most frequent causes of accidents vary by weekday.

**Top 10 Accident Hotspots (Areas)**
A countplot identifying the most accident-prone areas.

**Accident Severity by Road Surface Conditions**
A countplot to evaluate how road conditions correlate with accident severity.

**Accident Severity by Weather Conditions**
A countplot to analyze how weather conditions impact severity.

**Accident Severity by Light Conditions**
A countplot to understand the effect of lighting on accident outcomes.

**Heatmap: Causes of Accidents by Area**
A heatmap visualizing the frequency of accident causes across different areas.

**Conclusion:**
The visualizations provided several key insights into the patterns of traffic accidents:

Peak Accident Times: Most accidents occurred during daytime hours, especially in the early morning and late afternoon, indicating a strong link to daily commuting times.
Day-wise Trends: Weekdays showed higher accident counts compared to weekends, with Friday typically recording the highest.
Severity Analysis: Accident severity varied significantly with time, road surface conditions, light, and weather. Poor lighting, wet road surfaces, and adverse weather conditions were associated with a higher number of severe accidents.
Frequent Causes: The top 10 causes of accidents, such as lack of attention, failure to give priority, and speeding, consistently appeared across all days of the week, with some variation in frequency.

High-Risk Areas: Specific areas were identified as hotspots with a high frequency of accidents, suggesting the need for focused road safety interventions.

Environmental Conditions: Clear weather and daylight had the highest number of accidents, but this is likely due to more vehicles on the road during these conditions rather than the conditions being unsafe themselves.

Geospatial Trends: The heatmap highlighted that certain areas are more prone to specific types of accidents, which can help guide targeted preventive measures.
