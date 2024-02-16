# UK ROAD ACCIDENT ANALYSIS 2021-22
Road safety is a great concern across the world. Road traffic crashes result in the deaths of approximately 1.19 million people around the world each year and leave between 20 and 50 million people with non-fatal injuries. In addition to the human suffering caused by road traffic injuries, they also incur a heavy economic burden on victims and their families which ultimately affect the economic growth of the country. This is a data analysis done on the UK road accidents dataset for the years 2021 and 2022.
## PROBLEM STATEMENT
Goal is to analyse the UK based road accident data for 2021 and 2022 and create a visual, user-friendly dashboard that summarizes accident details, severity, weather conditions, and more. This dashboard will provide quick insights for informed decision-making and analysis. Clients want to create a road accident dashboard for the years 2021 and 2022 so that they can have insight into the requirements.
## DATA ANALYSIS PROCESS
### * Define the problem and gather required data 

Clients want to create a road accident dashboard, so that they can have insight into the requirements given below:

**Primary KPI**

-	Total causalities taken after the accident
-	Total causalities & percentage with respect to accident severity and max casualties by vehicle type

**Secondary KPI**

-	Total causalities with respect to vehicle type
-	Max casualties by road type
-	Monthly trend comparison of the causalities of CY 2021 & 2022
-	Distribution of total casualties by road surface
-	Relation between casualties by area/location, & by day/night

**Dataset**

The dataset contained a record of: Accident Date/time, severity, location, vehicle information, casualties information, weather, etc. The dataset is a demo dataset pulled from Kaggle.com, it was in a .xlsx format when downloaded. The dataset can be found here: (https://docs.google.com/spreadsheets/d/1msKWOTMOx3a13a7E89gW3xqxhuIsCpXT/edit?usp=drive_link&ouid=112636634511047423352&rtpof=true&sd=true)

### * Data cleaning and Transformation

The data analysis is done in MS Excel and used pivot tables and visualizations.

* Data Cleaning

In this phase, the dataset is thoroughly studied and ensured the accuracy and reliability of the data for further analysis. The data is cleaned by removing inconsistencies, errors, and duplicates. Example - replace the word “fetal” with “fatal” in the severity column.

* Data Transformation

To enhance data analysis, columns named as "Month", "Year", "Day_of_the_week" are created from the "Accident Date" column, allowing easy filtering and visualization based on these temporal dimensions. This data transformation ensures that the dashboard provides more meaningful insights and simplifies data exploration for users.

### * Data Analysis
  
Various statistical methods were applied to derive valuable insights from the data. Pivot tables and various charts and graphs are used for analysis and visualization. These are used as a foundation for building the dashboard. The KPIs are calculated with the help of pivot tables. Excel is utilized as a visualization tool to create attractive charts, graphs, and interactive visuals for presenting the data in an easily understandable manner.

![image](https://github.com/Grace-Elsa-George/Data-Analysis/assets/122536525/184f4dab-c40a-49e6-a5ad-d5907d6e9e64)

### * Data Visualization

Finally, a dashboard is created by inserting and customizing the pivot charts of corresponding pivot table. Inorder to make it interactive and user-friendly slicers are incorporated. Hyperlinks and connections are also added to necessary icons for the navigation.
The dashboard is given below:

![image](https://github.com/Grace-Elsa-George/Data-Analysis/assets/122536525/3c10e831-1056-4d75-a371-45558cc42a18)

The dashboard gives the following information on the accidents:

-	Totally 417,883 casualties occurred after accidents during the two-year period. Compared to 2022, most casualties were occured in 2021.

-	For both 2021 and 2022, maximum number of casualties happened in October and November. Minimum number of casualities happened in January and February.

-	Analysing the accident severity, Slight severity form the bulk of casualties 84.1% whereas there are only 1.7% Fatal severity casualties.

-	Accidents by car accounted for the highest number of casualties, contributing to 79.8% of the total. On the other hand, casualties were minimal in accidents involving other vehicle types.

-	Most of the total casualties were on Dry road surfaces (67%).

-	The urban areas had the majority of casualties after an accident (61%).

-	Single Carriageway road type caused maximum number of casualties (310.1K) and Slip Road caused minimim (5.1K).

-	73% of casulties take place in daylight condtion

### * Key Insights

- Due to urbanization and massive population, urban regions tend to have more road accident casualties.

- Cars cause more casualties because it is the most common means of road transportation. On the other hand, agricultural vehicles cause less road accident casualties because they are seldom used on roads.

- During snowy weather, fewer vehicles are used which results in lesser road accident casualties compared to when the road is dried.

### * Recommendations based on the Analysis

-	The road safety measure by the traffic police and other stakeholders must be active and focused during these high-risk periods such as in the months of October November.

-	More awareness should be provided to the common citizens since most of the accidents are happening by the private cars.

-	Extra safety measures should be placed Single Carriageway roads and they must be upgraded to double lane wherever possible.

-	More road safety measures and monitoring should be done in Urban areas since they are massive population areas.



