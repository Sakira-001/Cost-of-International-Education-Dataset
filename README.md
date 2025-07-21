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
1. **Total Countries Covered**: 22
2. **Total Universities Analyzed**: 84
3. **Total Programs Assessed**: 62
4. **Average Tuition Fee**: $25,432
5. **Average Total Education Cost (Tuition + Rent + Living Cost + Visa + Insurance)**: $42,750
6. **Most Expensive Country**: United States
7. **Least Expensive Country**:Poland
8. **Top 3 Universities by Tuition Fee**:
   - Stanford University: $57,000
   - Stanford University: $57,000
   - University of Melbourne: $52,300
9. **Most Expensive Program**: Computer Science
10. **Degree Level with Highest Total Cost**: PhD Programs
11. **City with Highest Average Living Cost**: San Francisco
12. **Exchange Rate Range (Local to USD)**: 0.11 – 1.36
13. **Program Types with Highest Cost Variation**:
   - Engineering
   - Business
   - Computer Science
14. **Cost Distribution by Degree Level**:
   - Bachelor's: 41%
   - Master's: 36%
   - PhD: 23%
15. **Top 5 Countries by Total Cost**:
   - United States
   - Australia
   - United Kingdom
   - Canada
   - Switzerland

---

## Insights & Conclusions
1. **The United States Has the Highest Total Education Cost**: Students looking to study in the U.S. face significantly higher combined costs (tuition, rent, living, visa, and insurance) compared to other countries, making it the most expensive destination overall.
2. **Tuition and Rent Are the Biggest Cost Drivers**: Across most countries, tuition and rent contribute the largest share to the total cost of studying abroad, with tuition alone sometimes accounting for over 50% of the total expenses.
3. **Poland and Turkey Offer the Most Affordable Education Options**: These countries have the lowest overall costs, making them attractive destinations for budget-conscious international students, especially for undergraduate programs.
4. **Master’s Programs Are More Prevalent but Also More Costly**: While Master’s programs make up a large portion of the dataset, they also tend to have higher tuition and associated living costs than Bachelor's programs in many countries.

---

## Tools & Techniques Used
1. **Power BI**:
   - Utilised Power Query Editor for data cleaning, formatting, and transformation.
   - Applied DAX (Data Analysis Expressions) to calculate Total Cost (Tuition + Visa + Insurance + Rent + Cost of Living) and other key metrics.
   - Integrated slicers and filters to allow dynamic comparisons by country, program, and institution.
   - Custom Visuals, including charts, to provide a clear insight presentation.
2. **PowerPoint**: Designed the dashboard background to enhance visual aesthetics and layout structure.

---

## Questions & Answers
### Q1: Which countries have the highest and lowest total education costs?
**Ans**: - Highest: The United States, United Kingdom, and Australia consistently show the highest total education costs, with expenses exceeding $45,000 in some cases.
         - Lowest: Countries like Poland, Germany, and Turkey offer the most affordable options, often staying under $20,000 for total annual costs.

### Q2: What are the major contributors to the total cost of studying abroad?
**Ans**: The largest contributors across most countries are: Tuition Fees, Rent/Housing, Cost of Living.

### Q3:  Which programs are associated with higher study costs?
**Ans**: STEM and MBA programs tend to have higher tuition and overall costs, especially in countries like the U.S., Canada, and the UK.

### Q4: Are there noticeable cost variations between public and private institutions?  
**Ans**: Yes, private institutions in high-cost countries like the U.S. and UK are significantly more expensive than public ones. 

---

## Recommendation
1. Prospective international students should consider countries like Poland, Turkey, or Germany, where total education costs are significantly lower, without compromising on educational quality.
2. Budgeting tools or cost breakdown checklists can help manage finances more effectively for students who are planning to travel abroad.
3. For countries like the U.S., UK, and Australia, institutions and advisors should actively share information on available scholarships, financial aid, or work-study options to help offset high total costs.
---

## Conclusion
This project highlights the wide disparities in international education costs and offers a centralised, interactive tool to help students make informed, data-driven decisions. By comparing tuition, living expenses, and other related costs across countries and programs, users can better assess affordability and plan their study-abroad journey effectively.
