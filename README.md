# WHO Covid-19 Global Data Analysis
![](images/WHO_Codid-19_image.jpg)





## Project Overview

### Introduction:
 Introduction:
The Covid-19 Global Analysis project aims to comprehensively analyze the impact of the Covid-19 pandemic on a global scale. By collecting, processing, and visualizing data from various sources, the project seeks to provide insights into the spread of the virus, its effects on public health systems, socio-economic implications, and response strategies adopted by different countries.


### Objectives:
- Compile and analyze the total number of new Covid-19 cases by region to identify regions experiencing increases in case counts.
- Identify and rank the top 10 countries with the highest number of new Covid-19 cases to highlight regions with the most significant outbreaks.
- Determine and rank the top 10 countries with the highest number of new Covid-19-related deaths to assess the impact of the pandemic on mortality rates.
- Analyze and report on new Covid-19 deaths by region to understand regional variations in mortality rates.
- Identify and rank the least 10 countries with new Covid-19 cases to highlight regions with lower incidence rates.
- Determine and rank the least 10 countries with new Covid-19-related deaths to assess regions with lower mortality rates.
- Identify and rank the top 10 countries with the highest number of Covid-19 vaccinations administered to evaluate progress in vaccination efforts.
- Analyze and report on the cumulative number of Covid-19 cases and deaths by year to assess the trajectory of the pandemic over time.
- Identify and rank the least 10 countries with the highest number of Covid-19 vaccinations administered to evaluate equitable access to vaccines.
- Develop and present a geospatial map illustrating new Covid-19 cases and deaths globally to visualize the geographic distribution and hotspots of the pandemic.

### Deliverables:
- Compilation and analysis of new Covid-19 cases by region, identifying areas with increased case counts.
- Identification and ranking of the top 10 countries with the highest new Covid-19 case counts, highlighting regional outbreaks.
- Ranking and analysis of the top 10 countries with the highest new Covid-19-related deaths, assessing mortality rates.
- Analysis and reporting on new Covid-19 deaths by region, understanding mortality rate disparities.
- Identification and ranking of the least 10 countries with new Covid-19 cases, assessing low-incidence regions.
- Assessment and ranking of the least 10 countries with new Covid-19-related deaths, examining lower mortality rates.
- Analysis and ranking of the top 10 countries with the highest Covid-19 vaccination rates, evaluating progress.
- Detailed analysis and reporting on cumulative Covid-19 cases and deaths by year, assessing pandemic trajectory.
- Identification and ranking of the least 10 countries with the highest Covid-19 vaccination rates, focusing on equitable access.
- Development of a geospatial map illustrating new Covid-19 cases and deaths globally, aiding visualization and analysis.



### About The Dataset
The "WHO Covid-19 Global Data Analysis" project involves analyzing comprehensive data provided by the World Health Organization (WHO) regarding the Covid-19 pandemic on a global scale. The data encompasses various aspects of the pandemic, including confirmed cases, deaths, recoveries, testing rates, vaccination coverage, and other relevant metrics. The data in this dataset was collected from the WHO Covid-19 dashboard data downloadable statistical release on the 31st of Decemember, 2023. This data is updated weekly. Users should note that, in addition to capturing new cases and deaths reported on any given day, updates are made retrospectively to correct counts on previous days as needed based on subsequent information received.. You can click [here](https://data.who.int/dashboards/covid19/data) to visit the WHO website and access the latest update.

The data source is made up of 4 datasets, and they are: vaccination-data.csv, vaccination-metadata, WHO-Covid-19-global-data.csv, and WHO-Covid-19-global-table-data.csv. You can access all of them [here](datasets)


### Skills Utilized
1. Data Transformation
2. Data Visualiziation
3. Descriptive Analytics
4. Critical Thinking and Problem Solving
5. Communication and Reporting


### Tools Utilized
1. Microsoft Excel
    - Was used to:
        1. Was used to save extracted data from WHO website,
        2. Transform,
        3. Load the dataset for this analysis.
     
2. Tableau (Was used to create dashboards for this analysis)
    - The following Tableau were incorporated:
        1. Calculated Fields
        2. Geospatial Analysis
        3. Page Navigation
        4. Filters
        5. Tooltips
        6. Buttons


### Data Transformation and Loading in Microsoft Excel and Tableau:
- Did the first data cleaning in Microsoft excel before loading the dataset to Tableau.
- Changed the data types to the appropriate data types in Tableau.



**Tableau Data View**

Tableau Data Screenshot                                                             |                                
:---------------------------------------------------------------------------------:|
![](images/Tableau_Data_Screenshot.png)


## Join/ Blend Data
There was no need to join or blend data as we have just a single table for this analysis.


## Tableau Visualization:
#### Dashboard View 1
![](images/WHO_%20Covid-19%20_Global_Analysis1.png)

#### Dashboard View 2
![](images/WHO_%20Covid-19%20_Global_Analysis2.png)


### WHO Project Analysis:
In this analysis, the following Key findings below were made:
- The Cumulative Covid-19 Cases at the time if this analysis was __78,104,887,614.__
- The New Cases was __773,119,173.__
- The Cases recorded as of Last 7 Days of this Analysis was __1,813,700.__
- The Cumulative Deaths was __924,851,078.__
- The Deaths recorded as of the Last 7 Days of this Analysis was __8,736.__
- The Number of Countries captured in this Analysis was __234.__


- <img src="images/Total_No_Of_New_Cases_By_Region.png" width="300">
- **Total Number of New Cases By Region:**
- This is an analysis of the World Health Organization (WHO) on the total number of new Covid-19 cases by region. It offers valuable insights into the global distribution and impact of the pandemic. Let's analyze each WHO region to glean insights into the patterns and trends observed:
- __EURO Region:__ The EURO region reported the highest number of new Covid-19 cases, totaling approximately 277,745,749 cases. This region encompasses countries in Europe, which have been significantly affected by the pandemic since its onset. The high number of cases in this region reflects the widespread transmission of the virus and the challenges faced in controlling its spread despite advanced healthcare systems and public health interventions.
- __WPRO Region:__ The WPRO region reported a substantial number of new Covid-19 cases, totaling around 207,767,484 cases. This region comprises countries in the Western Pacific, including populous nations like China and Japan. The significant case count in this region highlights the global reach of the pandemic. 
- __AMRO Region:__ The AMRO region reported a considerable number of new Covid-19 cases, totaling approximately 192,633,514 cases. This region encompasses countries in the Americas, including the United States, Brazil, and Mexico, which have been heavily impacted by the pandemic. Factors such as population density, healthcare infrastructure, and socio-economic disparities contribute to the high case count in this region.
- __SEARO Region:__ The SEARO region reported a moderate number of new Covid-19 cases, totaling around 61,226,840 cases. This region includes countries in Southeast Asia, such as India, Indonesia, and Thailand. While the case count in this region is lower compared to others, it still represents a significant burden of disease. 
- __EMRO Region:__ The EMRO region reported a comparatively lower number of new Covid-19 cases, totaling around 23,408,461 cases. This region includes countries in the Eastern Mediterranean, such as Iran, Saudi Arabia, and Egypt. While the case count in this region is lower compared to others, it still represents a significant challenge for healthcare systems. 
- __AFRO Region:__ The AFRO region reported the lowest number of new Covid-19 cases, totaling approximately 9,026,243 cases. This region comprises countries in Africa, where the pandemic has had a varied impact, with some countries experiencing significant outbreaks while others have been relatively spared. Factors such as limited testing capacity, infrastructure challenges, and younger populations may contribute to the lower case count in this region.



- <img src="images/Top10_Countries_With_New_Cases.png" width="300">
- **Top 10 Countries With New Cases:**
- In this analysis on the top 10 countries with new Covid-19 cases, insights were offered into the global distribution and magnitude of the pandemic. Let's analyze each country to understand the patterns and trends observed:
- __United States of America (USA):__ The USA reported the highest number of new Covid-19 cases, totaling approximately 103,436,829 cases. The country experienced multiple waves of infections throughout the pandemic, with varying levels of containment measures and vaccination efforts. Factors such as population density, healthcare disparities, and public health policies have influenced the trajectory of the pandemic in the USA.
- __India:__ India reported a substantial number of new Covid-19 cases, totaling around 45,008,620 cases. The country experienced a devastating surge in cases during the second wave of the pandemic, overwhelming healthcare systems and leading to significant morbidity and mortality. Factors such as population density, limited healthcare resources, and socio-economic disparities contributed to the severity of the outbreak in India.
- __France:__ France reported a high number of new Covid-19 cases, totaling approximately 38,997,490 cases. The country implemented various public health measures to control the spread of the virus, including lockdowns, social distancing, and mask mandates. Despite these efforts, France continued to face challenges in managing the pandemic, particularly with the emergence of new variants and vaccine distribution issues.
- __Germany:__ Germany reported a significant number of new Covid-19 cases, totaling around 38,437,756 cases. The country implemented aggressive testing and contact tracing strategies to control transmission, along with vaccination campaigns to boost immunity. However, the emergence of new variants and pandemic fatigue posed challenges to Germany's efforts to contain the virus.
- __Brazil:__ Brazil reported a substantial number of new Covid-19 cases, totaling approximately 37,519,960 cases. The country faced significant challenges in controlling the pandemic, with political and logistical issues hampering response efforts. Brazil's healthcare system was strained by the high number of cases, leading to shortages of medical supplies and overwhelmed hospitals.
- __Italy:__ Italy reported a considerable number of new Covid-19 cases, totaling around 26,495,903 cases. The country was one of the early epicenters of the pandemic, experiencing a devastating outbreak in early 2020. Italy has since implemented stringent measures to contain the virus, including lockdowns and vaccination campaigns, but continued to face challenges in managing the pandemic.
- __United Kingdom of Great Britain and Northern Ireland (UK):__ The reported a significant number of new Covid-19 cases, totaling approximately 24,812,582 cases. The country implemented a phased approach to pandemic response, including lockdowns, mass testing, and vaccine rollouts. Despite vaccination efforts, the UK faced challenges with new variants and surges in cases, requiring ongoing vigilance and public health measures.
- __Russian Federation:__ The Russian Federation reported a substantial number of new Covid-19 cases, totaling around 23,576,556 cases. The country implemented a combination of public health measures and vaccination campaigns to control transmission and protect public health. However, there were still challenges in ensuring equitable access to vaccines and addressing vaccine hesitancy among certain populations.
- __Mexico:__ Mexico reported a moderate number of new Covid-19 cases, totaling around 7,702,731 cases. The country faced challenges in managing the pandemic, including limited healthcare resources and socio-economic disparities. Mexico implemented public health measures such as mask mandates and social distancing guidelines to mitigate transmission, but challenges persisted in controlling the spread of the virus.
- __Peru:__ Peru reported a moderate number of new Covid-19 cases, totaling around 4,530,620 cases. The country implemented various public health measures and vaccination campaigns to control transmission and protect public health. However, there were challenges in ensuring compliance with public health guidelines and addressing socio-economic disparities in access to healthcare and vaccines.
