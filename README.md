# Cost-of-International-Education-Dataset
This Cost of International Education dataset compiles detailed financial information for students pursuing higher education abroad. It covers multiple countries, cities, and universities around the world, capturing the full tuition and living expenses spectrum alongside key ancillary costs. This dataset is built on empathy, and I selected it because of its connection to education, as fewer people can afford international education worldwide.

---

## Table of Contents
1. [Overview](#overview)
2. [Raw Data](#raw-data)
3. [Dashboard & Dashboard Features](#dashboard-features)
4. [Data Cleaning Process](Data--cleaning--process&preprocessing)
5. [Key Metrics](#key-metrics)
6. [Insights & Conclusions](#insights--conclusions)
7. [Tools & Techniques Used](#tools--techniques-used)
8. [Questions & Answers](#questions--answers)
9. [Recommendation](#Recommendation)
10. [Conclusion](#Conclusion)
11. [Author](#author)

---

## Overview
This project presents an interactive Power BI dashboard built using a dataset on the cost of international education across various countries, cities, and universities. It includes key financial metrics such as tuition fees, rent, living expenses, visa fees, insurance, and exchange rates. The dashboard provides a centralized view for comparing study costs across programs and degree levels (Bachelor, Master, PhD), helping prospective students, consultants, and researchers evaluate affordability and identify cost-effective study destinations.

---

## Raw Data
The raw data for this dashboard includes a comprehensive dataset of the International Education Costs dataset. It consists of the following fields:

1. **Program**: Name of the academic program (e.g., Computer Science, Engineering).
2. **Degree Level**: e.g., Bachelor's, Master's, PhD.
3. **University**: Name of the institution offering the program.
4. **Country**: The country where the university is located.
5. **City**: Specific city of the institution.
6. **Tuition (USD)**: Annual or program-based tuition fees in USD.
7. **Living Cost**: Estimated monthly or annual living expenses (excluding rent).
8. **Rent**: Average cost of student housing or accommodation.
9. **Visa Fee**: Application or processing fee for a student visa.
10. **Insurance**: Health/travel insurance cost for international students.
11. **Exchange Rate**: Conversion rate to USD from local currency.
12. **Total Cost**: Calculated field: sum of Tuition, Living Cost, Rent, Visa Fee, and Insurance.
13. **Living Cost Index**: Numerical index indicating the cost of living in the city.

---

### Data Cleaning Process in Power Query
- **Removed Duplicates**
- **Removed Unnecessary Characters**
- **Changed Data Types**
- **Renamed Columns for Clarity**
- **Handled Null Values**
- **Created a New Column for Total Cost**

---

## Dashboard Features
- **Interactive Filters**: Users can filter data by country, city, university, degree level, and academic program to explore education costs from different perspectives.
- **Visualizations**: Users can filter data by country, city, university, degree level, and academic program to explore education costs from different perspectives.
- **Cost Breakdown**: Key financial elements such as tuition, rent, visa fees, insurance, and living expenses are individually displayed and aggregated for complete transparency.
- **Top-N Highlights**: Charts identify the top countries and universities with the highest education expenses, helping users recognise high-cost destinations quickly.
- **Highlight Cards (KPIs)**: Summary cards display key metrics like average tuition, total cost, and number of universities or countries covered, offering quick insights at a glance.
- **Program-Specific Insights**: Side-by-side comparisons reveal which programs (e.g., Computer Science, Business) have the highest total costs across locations.
- **User-Friendly Design**: Consistent colour themes, clear titles, and structured layouts improve readability and guide users through the data story effectively.
- **Dynamic Interactivity**: All visuals respond in real time to slicer selections, enabling users to conduct focused analysis based on specific study destinations, program types, or cost components.

---

## Key Metrics
1. **Total Reported Collisions**: 91,286
2. **Total Injuries**: 45,317
   - Persons Injured: 37,198
   - Pedestrians Injured: 4,211
   - Cyclists Injured: 1,932
   - Motorists Injured: 1,976
3. **Total Fatalities**: 276
   - Persons Killed: 213
   - Pedestrians Killed: 39
   - Cyclists Killed: 12
   - Motorists Killed: 12
4. **Borough with Most Collisions**: Brooklyn
5. **Most Common Contributing Factor**: Driver Inattention/Distraction
6. **Peak Collision Hours**: Between 3 PM – 6 PM
7. **Collisions by Vehicle Type**:
   - Passenger Vehicles: 58%
   - Commercial Vehicles: 18%
   - Two-Wheelers (Motorcycles, Bicycles): 9%
   - Emergency Services: 3%
   - Others: 6%
   - Unknown/Not Reported: 6%
8. **Seasonal Pattern**: Highest collisions recorded in October, lowest in February
9. **Most Affected Demographic**: Motorists and pedestrians injured in Brooklyn and Queens
10. **Location Hotspots**: Most incidents occurred in densely populated areas with high traffic volume

---

## Insights & Conclusions
1. **Leading Causes of Collisions**:
   - The top contributing factor to collisions is "Unspecified", meaning a lack of detailed reporting.
   - Driver inattention/distraction is the most reported cause, emphasizing the need for awareness campaigns on focused driving.
2. **Fatalities Across Boroughs**:
   - Brooklyn has the highest fatalities among pedestrians, motorists, and cyclists.
   - Motorists experience the most fatalities overall, suggesting that driver safety improvements are needed.
3. **Vehicle Types in Collisions**:
   - Passenger vehicles account for the highest number of collisions, far exceeding any other vehicle type across all boroughs.
   - Bicycles, taxis, motorcycles, and buses contribute to accidents but at significantly lower numbers compared to passenger vehicles.
   - Brooklyn leads in overall collisions, followed by Queens and the Bronx, possibly due to higher traffic density and population.

---

## Tools & Techniques Used
1. **Power BI**:
   - Power Query Editor for extensive data cleaning and transformation.
   - DAX (Data Analysis Expressions) to calculate key metrics like total collisions, injuries, fatalities, and percentage breakdowns.
   - Slicers for dynamic filtering by borough, vehicle type, month, and contributing factors.
   - Custom Visuals including bar charts, pie charts, stacked columns, KPIs, and heatmaps for clear insight presentation.
2. **Figma**: Designed visual mockups and layout guides to ensure a clean, user-friendly dashboard interface.

---

## Questions & Answers
### Q1: Compare the % of total accidents by month. Do you notice any seasonal patterns? 
**Ans**: Yes, a clear seasonal pattern emerges. The highest percentage of accidents occurred in October, followed by June and August. The months with the lowest accident rates were February and January.

### Q2: Break down accident frequency by day of week and hour of day. Based on this data, when do accidents occur most frequently?
**Ans**: - Accidents peak sharply around midnight (12:00 AM) — likely due to the timestamp default or batch reporting practices — followed by a steady increase from 6:00 AM, with consistent spikes between 8:00 AM to 6:00 PM, especially around 3:00 PM to 6:00 PM, coinciding with afternoon rush hours.
         - By Day of Week: Fridays have the highest accident frequency, followed closely by Thursdays and Wednesdays.
Weekends (especially Sundays) see fewer incidents, likely due to reduced commuting traffic.

### Q3:  On which particular street were the most accidents reported? What does that represent as a % of all reported accidents? 
**Ans**: The street with the most reported accidents was Brooklyn.

### Q4: What was the most common contributing factor for the accidents reported in this sample (based on 
Vehicle 1)? What about fatal accidents specifically?  
**Ans**: - The most common contributing factor across all accidents (based on Vehicle 1) was Unspecified.
         - For fatal accidents specifically, the leading contributing factor remained Unspecified.

---

## Recommendation
1. Enhance Driver Awareness & Distraction Prevention Campaigns: Implementing stricter penalties for distracted driving and conducting public awareness campaigns on focused driving and accident prevention.
2. Improve Traffic Control & Law Enforcement: Increase traffic patrols in high-collision areas and enforce speed limits, right-of-way laws, and lane discipline more strictly.
3. Develop Safer Infrastructure for Cyclists & Pedestrians: Expand dedicated bike lanes and pedestrian-friendly zones and install more traffic calming measures (e.g., speed bumps, pedestrian islands).
4. Targeted Safety Measures in High-Collision Boroughs: Brooklyn & Queens: Implement city-wide road safety programs due to high fatalities.
---

## Conclusion
This project successfully analyzed NYC traffic accident data to identify key patterns and risk factors. The insights gathered can help inform safety initiatives, improve traffic management, and reduce accident occurrences through data-driven decisions.
