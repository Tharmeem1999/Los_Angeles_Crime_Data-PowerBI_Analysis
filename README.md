# Los Angeles Crime Data (January 2020 and December 2023) 

## Introduction

Welcome to the **Los Angeles Crime Data Analysis**! This Power BI report analyzes an extensive dataset of official crime records reported in Los Angeles between January 2020 and December 2023. The dataset, sourced from Kaggle, includes information on reported crimes such as dates, locations, crime descriptions, victim demographics, premises, weapons used, and case statuses.

## Data Source

The dataset used in this analysis is sourced from Kaggle:  
[Los Angeles Crime Data (2020-2023)](https://www.kaggle.com/datasets/asaniczka/crimes-in-los-angeles-2020-2023)

## Visualizations

This analysis consists of two pages with the following visualizations:

### Page 1: Crime Overview

1. **Map Visualization:** Displays the geographic distribution of crime incidents in Los Angeles, with bubble sizes representing the count of incidents (based on the Division Number column).
2. **Stacked Bar Chart:** Shows crime incidents by area, with the Area Name on the y-axis and incident counts on the x-axis.
3. **Slicer:** Allows filtering by Area Name.
4. **Stacked Bar Chart:** Visualizes crime incidents by type, with the Crime Description on the y-axis and incident counts on the x-axis.
5. **Line Chart:** Illustrates quarterly crime trends, with the Date Reported on the x-axis and incident counts on the y-axis.

### Page 2: Victim & Circumstance Analysis

1. **Clustered Column Chart:** Analyzes crime incidents by Victim Age, with Age on the x-axis and incident counts on the y-axis.
2. **Treemap:** Shows crime incidents by Victim Ethnicity, categorized by the Victim Descent column with incident counts as values.
3. **Donut Chart:** Displays the gender distribution of victims, with counts of incidents as values and Victim Sex as details.
4. **Stacked Bar Chart:** Visualizes crime incidents by location type, with Premise Description on the y-axis and incident counts on the x-axis.
5. **Stacked Bar Chart:** Highlights weapon types used in crimes, with Weapon Description on the y-axis and incident counts on the x-axis.

## Snapshots of the report

![Page 1](https://github.com/user-attachments/assets/848660fe-ba89-4e50-b2d4-ae644e69eb7d)  
![Page 2](https://github.com/user-attachments/assets/032dabe7-2e50-491c-8e5e-009787066e77)

## Key Insights

### [1] Crime Incidents by Area

Top 5 areas with the highest number of crime incidents:  
1. **Central:** 57,691 incidents  
2. **77th Street:** 53,631 incidents  
3. **Pacific:** 49,850 incidents  
4. **Southwest:** 47,858 incidents  
5. **Hollywood:** 45,018 incidents  

**Insight:** The Central area has the highest number of reported incidents, with 57,691 cases.

---

### [2] Crime Incidents by Type

Top 5 most common crime types:  
1. **Vehicle - Stolen:** 91,473 incidents  
2. **Battery - Simple Assault:** 67,976 incidents  
3. **Theft of Identity:** 53,467 incidents  
4. **Burglary from Vehicle:** 52,611 incidents  
5. **Burglary:** 51,916 incidents  

**Insight:** "Vehicle - Stolen" is the most common crime, with 91,473 incidents reported.

---

### [3] Quarterly Crime Trends

**Insight:** The highest number of incidents (60,629) occurred in Q2 of 2022.

---

### [4] Crime Incidents by Victim Age

**Insight:** More than 15,000 incidents were reported for victims aged between 24 and 36.

---

### [5] Crime Incidents by Victim Ethnicity

Top 3 victim ethnicities:  
1. **H (Hispanic):** 261,145 incidents  
2. **W (White):** 173,440 incidents  
3. **B (Black):** 120,896 incidents  

**Insight:** Hispanics are the most victimized ethnicity, with 261,145 incidents.

---

### [6] Victim Gender Distribution

Victim gender breakdown:  
- **Female:** 313,468 incidents (36.75%)  
- **Male:** 351,362 incidents (41.19%)  
- **X:** 188,120 incidents (22.06%)  

**Insight:** Males are the most victimized gender group.

---

### [7] Crime Locations

Top 5 crime locations:  
1. **Street:** 216,018 incidents  
2. **Single-Family Dwelling:** 144,367 incidents  
3. **Multi-Unit Dwelling:** 104,461 incidents  
4. **Parking Lot:** 59,551 incidents  
5. **Other Business:** 40,412 incidents  

**Insight:** Streets are the most common crime locations, with 216,018 incidents.

---

### [8] Weapon Types Used in Crimes

Top 5 weapon types:  
1. **Null (Unidentified):** 556,202 incidents  
2. **Strong-Arm:** 159,021 incidents  
3. **Unknown/Other Weapon:** 31,728 incidents  
4. **Verbal Threat:** 21,767 incidents  
5. **Handgun:** 18,330 incidents  

**Insight:** Most crimes involved unidentified weapons, totaling 556,202 incidents.

---

## Data Preparation

The dataset required significant modification in Power Query, including data type adjustments and value replacements. For example, in the `Victim Sex` column, any value not matching "M" (Male) or "F" (Female) was replaced with "X"
