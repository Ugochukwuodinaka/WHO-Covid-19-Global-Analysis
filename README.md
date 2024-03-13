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


- <img src="images/Reported_Cases_By_Region.png" width="300">
- **Reported Cases By Region:**
- This is an analysis of the World Health Organization (WHO) on the total number of new Covid-19 reported cases by region. It offers valuable insights into the global distribution and impact of the pandemic. Let's analyze each WHO region to glean insights into the patterns and trends observed:
- __EURO Region:__ The EURO region reported the highest number of new Covid-19 cases, totaling approximately 277,745,749 cases. This region encompasses countries in Europe, which have been significantly affected by the pandemic since its onset. The high number of cases in this region reflects the widespread transmission of the virus and the challenges faced in controlling its spread despite advanced healthcare systems and public health interventions.
- __WPRO Region:__ The WPRO region reported a substantial number of new Covid-19 cases, totaling around 207,767,484 cases. This region comprises countries in the Western Pacific, including populous nations like China and Japan. The significant case count in this region highlights the global reach of the pandemic. 
- __AMRO Region:__ The AMRO region reported a considerable number of new Covid-19 cases, totaling approximately 192,633,514 cases. This region encompasses countries in the Americas, including the United States, Brazil, and Mexico, which have been heavily impacted by the pandemic. Factors such as population density, healthcare infrastructure, and socio-economic disparities contribute to the high case count in this region.
- __SEARO Region:__ The SEARO region reported a moderate number of new Covid-19 cases, totaling around 61,226,840 cases. This region includes countries in Southeast Asia, such as India, Indonesia, and Thailand. While the case count in this region is lower compared to others, it still represents a significant burden of disease. 
- __EMRO Region:__ The EMRO region reported a comparatively lower number of new Covid-19 cases, totaling around 23,408,461 cases. This region includes countries in the Eastern Mediterranean, such as Iran, Saudi Arabia, and Egypt. While the case count in this region is lower compared to others, it still represents a significant challenge for healthcare systems. 
- __AFRO Region:__ The AFRO region reported the lowest number of new Covid-19 cases, totaling approximately 9,026,243 cases. This region comprises countries in Africa, where the pandemic has had a varied impact, with some countries experiencing significant outbreaks while others have been relatively spared. Factors such as limited testing capacity, infrastructure challenges, and younger populations may contribute to the lower case count in this region.



- <img src="images/Top10_Countries_With_New_Cases.png" width="300">
- **Top 10 Countries With New Cases:**
- In this analysis on the top 10 countries with new Covid-19 cases, insights were offered into the global distribution and magnitude of the pandemic. Let's analyze each country to understand the patterns and trends observed:
- __United States of America:__ Leading the list with 103,436,829 new cases, the USA remained heavily impacted by the pandemic, highlighting ongoing challenges in containment efforts.
- __India:__ Following closely with 45,008,620 new cases, India continued to experience significant transmission rates despite recent vaccination efforts and containment measures.
- __France:__ France reported 38,997,490 new cases, indicating substantial community transmission and the need for stringent public health interventions to curb the spread.
- __Germany:__ With 38,437,756 new cases, Germany faced persistent challenges in controlling outbreaks and ensuring healthcare capacity amidst the pandemic.
- __Brazil:__ Brazil reported 37,519,960 new cases, reflecting the widespread transmission of the virus and the strain on the country's healthcare system.
- __Italy:__ Italy reported 26,495,903 new cases, demonstrating the continued impact of the pandemic on European countries and the importance of coordinated response efforts.
- __United Kingdom of Great Britain and Northern Ireland:__ The UK reported 24,812,582 new cases, underscoring the need for continued vigilance and adherence to public health guidelines to mitigate transmission rates.
- __Russian Federation:__ Russia reported 23,576,556 new cases, exposing the global reach of the pandemic and the challenges in controlling transmission in densely populated regions.
- __Mexico:__ Mexico reported 7,702,731 new cases, indicating significant transmission rates and the need for enhanced testing, contact tracing, and vaccination efforts.
- __Peru:__ Peru reported 4,530,620 new cases, underlining the impact of the pandemic on countries with limited healthcare infrastructure and resources.




- <img src="images/Top10_Countries_By_Reported_Cases.png" width="300">
- **Top 10 Countries By Reported Cases:**
- In the analysis of the top 10 countries with the highest number of reported Covid-19 deaths, i  provided critical insights into the severity of the pandemic's impact on global mortality rates:
- __United States of America:__ Leading the list with 1,144,877 new deaths, the USA continued to face significant challenges in managing the pandemic and reducing mortality rates.
- __Brazil:__ Brazil follows closely with 702,116 new deaths, highlighting the devastating toll of the virus on the country's population and healthcare system.
- __India:__ India reported 533,333 new deaths, indicating the widespread impact of the pandemic despite recent efforts to ramp up vaccination and containment measures.
- __Russian Federation:__ With 400,935 new deaths, Russia faces ongoing challenges in controlling transmission and ensuring access to healthcare services for Covid-19 patients.
- __Mexico:__ Mexico reported 334,947 new deaths, emphasizing the need for continued vigilance and public health interventions to mitigate the spread of the virus.
- __United Kingdom of Great Britain and Northern Ireland:__ The UK reported 232,112 new deaths, underlining the importance of maintaining effective public health measures and vaccination campaigns.
- __Peru:__ Peru reported 221,575 new deaths, highlighting the impact of the pandemic on countries with limited healthcare infrastructure and resources.
- __Italy:__ Italy reported 193,743 new deaths, demonstrating the persistent challenges in controlling transmission and reducing mortality rates despite early outbreaks.
- __Germany:__ Germany reported 174,979 new deaths, indicating the ongoing need for robust public health responses and vaccination campaigns to protect vulnerable populations.
- __France:__ France reported 167,985 new deaths, reflecting the continued burden of the pandemic on healthcare systems and the importance of coordinated international efforts to combat the virus.



- <img src="images/Reported_Deaths_By_Region.png" width="300">
- **Reported Deaths By Region:**
- In the data on reported Covid-19 deaths by WHO region, key insights were provided into the distribution and impact of mortality rates globally:
- __AMRO (Americas):__ With 2,973,030 new deaths, the AMRO region, comprising the Americas, faces significant mortality rates, reflecting the severity of the pandemic in this region.
- __EURO (Europe):__ EURO reported 2,259,637 new deaths, indicating substantial mortality rates and the toll of the pandemic on European countries despite advanced healthcare systems.
- __SEARO (Southeast Asia):__ SEARO reported 808,166 new deaths, highlighting the impact of the pandemic on countries in Southeast Asia and the need for enhanced healthcare infrastructure and resources.
- __WPRO (Western Pacific):__ WPRO reported 418,729 new deaths, indicating the toll of the pandemic on countries in the Western Pacific region and the challenges in controlling transmission rates.
- __EMRO (Eastern Mediterranean):__ EMRO reported 351,854 new deaths, demonstrating the impact of the pandemic on countries in the Eastern Mediterranean region and the importance of coordinated response efforts.
- __AFRO (Africa):__ AFRO reported 174,367 new deaths, indicating comparatively lower mortality rates in the African region but underscoring the need for continued vigilance and public health interventions.



- <img src="images/Least10_Countries_By_Reported_Cases.png" width="300">
- **Least 10 Countries By Reported Cases:**
- In this analysis of the data on the least 10 countries by reported Covid-19 cases, i shedded light on regions experiencing minimal transmission rates:
- __Wallis and Futuna:__ With 3,550 new cases, Wallis and Futuna demonstrate minimal transmission rates, potentially attributed to its small population and remote location.
- __Saint Pierre Miquelon:__ Reporting 3,426 new cases, Saint Pierre Miquelon's low population density and stringent border controls likely contribute to its low transmission rates.
- __Tuvalu:__ Tuvalu reported 2,943 new cases, benefiting from its isolated location and small population, which aids in controlling the spread of the virus.
- __Saint Helena:__ With 2,166 new cases, Saint Helena's isolated geographical location and limited population contribute to its low transmission rates.
- __Falkland Islands (Malvinas):__ Reporting 1,923 new cases, the Falkland Islands benefit from their remote location and sparse population, which may help contain the spread of the virus.
- __Montserrat:__ Montserrat reports 1,403 new cases, likely influenced by its small population size and effective public health measures.
- __Niue:__ With 895 new cases, Niue's low population density and geographic isolation contribute to its ability to control transmission rates effectively.
- __Tokelau:__ Tokelau reports only 80 new cases, benefitting from its remote location and small population, which aids in preventing widespread transmission.
- __Holy See:__ Reporting 20 new cases, the Holy See's small population and strict measures likely contribute to its minimal transmission rates.
- __Pitcairn:__ With only 4 new cases, Pitcairn's extremely low population density and isolation help keep transmission rates negligible.




- <img src="images/Least10_Countries_By_Rreported_Deaths.png" width="300">
- **Least 10 Countries By Reported Deaths:**
- In this analysis, the countries listed among the least 10 by reported Covid-19 deaths exhibit minimal mortality rates, which may indeed be influenced by factors such as low population density:
- __Burundi:__ With 15 new deaths, Burundi's low population density, favorable geographical and racial factors, and effective containment measures likely contributed to its minimal mortality rates.
- __Vanuatu:__ Reporting 14 new deaths, Vanuatu's remote location and sparse population may help limit the spread of the virus and subsequent fatalities.
- __Tonga:__ Tonga reported 12 new deaths, benefitting from its isolated geographical location and small population, which aids in preventing widespread transmission and fatalities.
- __Anguilla:__ With 12 new deaths, Anguilla's low population density and stringent public health measures likely contribute to its minimal mortality rates.
- __Palau:__ Reporting 9 new deaths, Palau's remote location and small population size likely help in containing the spread of the virus and reducing fatalities.
- __Wallis and Futuna:__ With 8 new deaths, Wallis and Futuna's small population and effective containment efforts contribute to its low mortality rates.
- __Montserrat:z-- Montserrat reported 8 new deaths, likely influenced by its small population size and effective public health measures.
- __Cook Islands:__ With only 2 new deaths, the Cook Islands benefit from their remote location and sparse population, which aids in preventing widespread transmission and fatalities.
- __Tuvalu:__ Reporting 1 new death, Tuvalu's low population density and geographical isolation contribute to its ability to keep mortality rates minimal.
- __Nauru:__ With only 1 new death, Nauru's small population and strict measures likely contribute to its minimal mortality rates.



- <img src="images/Top10_Countries_With_Most_Vaccinations.png" width="300">
- **Top 10 Countries With Most Vaccinantions:**
- The top 10 countries with the highest number of Covid-19 vaccinations achieved remarkable progress in immunizing their populations, driven by several contributing factors. Below is my analysis on this:
- __China:__ China's large population and robust vaccination infrastructure facilitated the administration of over 3.5 billion vaccine doses, indicating an extensive vaccination campaign.
- __India:__ India's vast vaccination efforts, supported by its populous demographics and vaccination drive, resulted in over 2.2 billion vaccine doses administered.
- __United States of America:__ The USA's efficient vaccine distribution network and prioritization of vaccination led to the administration of over 700 million vaccine doses, demonstrating its commitment to widespread immunization.
- __Brazil:__ Brazil's active vaccination campaign, coupled with its substantial population, contributed to the administration of over 500 million vaccine doses, marked significant progress in the country's immunization efforts.
- __Indonesia:__ Indonesia's accelerated vaccination program, supported by government initiatives and public health campaigns, resulted in the administration of over 440 million vaccine doses.
- __Japan:__ Japan's efficient vaccination rollout and nationwide distribution channels led to the administration of over 400 million vaccine doses, signaling progress in achieving herd immunity.
- __Bangladesh:__ Bangladesh's proactive vaccination strategy and collaboration with international partners facilitated the administration of over 360 million vaccine doses, which aided in controlling the spread of the virus.
- __Pakistan:__ Pakistan's vaccination efforts, bolstered by government initiatives and public awareness campaigns, led to the administration of over 340 million vaccine doses, contributing to immunity levels within the population.
- __Vietnam:__ Vietnam's comprehensive vaccination program, combined with public health measures, resulted in the administration of over 260 million vaccine doses, enhancing protection against Covid-19.
- __Mexico:__ Mexico's vaccination campaign, supported by government efforts and collaboration with vaccine manufacturers, led to the administration of over 220 million vaccine doses, aiding in the fight against the pandemic.


- <img src="images/Least10_Countries_With_Most_Vaccinations.png" width="300">
- **Least 10 Countries With Lowest Vaccinantions:**
- This analysis is on the least 10 countries with the lowest number of Covid-19 vaccinations. These countries have faced challenges in achieving widespread immunization, influenced by various contributing factors:
- __Burundi:__ Burundi's low vaccination rate of 41,538 vaccinations may be attributed to limited access to vaccines, logistical challenges, and vaccine hesitancy among the population.
- __British Virgin Islands:__ With 41,453 vaccinations, the British Virgin Islands' small population and logistical constraints may have hindered vaccine distribution and administration efforts.
- __Cook Islands:__ With 40,080 vaccinations, the Cook Islands' remote location and dependence on external support for vaccine supply and distribution may have contributed to its low vaccination rate.
- __Nauru:__ Nauru's low vaccination count of 32,157 indicates that Nauru's limited healthcare infrastructure and small population size may have impacted its ability to procure and administer vaccines effectively.
- __Tuvalu:__ Tuvalu's geographical isolation and logistical challenges in vaccine distribution may have resulted in its low vaccination rate of 26,783.
- __Anguilla:_- Anguilla's small population and reliance on external support for vaccine procurement and distribution may have contributed to its low vaccination rate of 24,864.
- __Wallis and Futuna:__ With a low vaccination rate of 17,303, Wallis and Futuna's remote location and limited healthcare resources may have affected its capacity to administer vaccines efficiently.
- __Tokelau:__ With 6,342 vaccinations, Tokelau's remote and sparsely populated islands may have faced logistical hurdles in vaccine delivery and limited access to healthcare facilities.
- __Niue:__ With 4,923 vaccination counts, Niue's small population and reliance on external assistance for vaccine procurement and distribution may have impacted its vaccination efforts.
- _-Montserrat:__ Montserrat's small population size and limited healthcare infrastructure may have posed challenges in vaccine procurement, distribution, and administration. These may have attributed to its low vaccination rate of 4,619.



- <img src="images/Cumulative_Reported_Cases_And_Deaths_By_Year.png" width="300">
- **Cumulative Number of Reported Cases And Reported Deaths By Year:**
- The cumulative number of reported Covid-19 cases and deaths by year provides valuable insights into the trajectory of the pandemic, The key insights below:
- __2020:__ In 2020, there were 80.3 million reported cases and 1.9 million reported deaths globally, marking the onset of the pandemic and the initial surge in infections and fatalities.
- __2021:__ The year 2021 saw a significant increase in both reported cases and deaths, with 200.3 million reported cases and 3.5 million reported deaths reported, reflecting the widespread transmission of the virus and the strain on healthcare systems.
- __2022:__ Despite efforts to control the spread of the virus, 2022 witnessed a continued rise in reported cases to 424 million, while reported deaths declined to 1.2 million, indicating advancements in medical treatments and vaccination efforts.
- __2023:__ By 2023, the number of reported cases decreased to 68.5 million, while reported deaths further declined to 294,371, suggesting improved containment measures, vaccination coverage, and public health interventions.



## Tableau Visualization Dashboard:
You can view and interact with this dashboard report [here](https://public.tableau.com/app/profile/ugo.bruno/viz/WHOCOVID-19GLOBALANALYSIS_17040613047730/Dashboard1?pu)



## Recommendations On Reducing The Global Spread of Covid-19:
- __Vaccination Equity:__ The World Health Organization should ensure equitable access to Covid-19 vaccines worldwide, they should prioritizing distribution to vulnerable populations and low-income countries to curb transmission and mitigate the emergence of new variants.
- __Enhanced Surveillance and Testing:__  The World Health Organization in collaboration with countries needs to implement robust surveillance systems and expand testing capacity globally to detect and monitor Covid-19 cases effectively, enabling prompt responses and containment measures.
- __Public Health Measures:__ They should promote adherence to proven public health measures such as mask-wearing, physical distancing, hand hygiene, and ventilation, particularly in high-risk settings, to reduce transmission and protect vulnerable populations.
- __International Collaboration:__ Tthey should foster international cooperation and coordination in sharing data, resources, and expertise to strengthen pandemic response efforts, they should also facilitate vaccine production and distribution, and address global health disparities.
- __Risk Communication:__ They can enhance communication strategies to disseminate accurate information, combat misinformation and vaccine hesitancy, and empower communities to make informed decisions about Covid-19 prevention and vaccination.
- __Support Healthcare Systems:__ In collaboration with countries of the world, they can provide adequate resources, funding, and support to healthcare systems worldwide to enhance capacity for Covid-19 treatment, vaccination, and preparedness for future pandemics.






