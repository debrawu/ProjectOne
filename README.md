# Project Title: COVID-19

## Team Members: Debra Wu, Michael Bien, Jinah Porter, Lupita Lopez
## Git Repository Link: https://github.com/debrawu/ProjectOne.git

### Project Description/ Outline

WHO (World Health Organization) defines the pandemic as “an epidemic occurring worldwide, or over a very wide area, crossing international boundaries and usually affecting a large number of people". COVID-19 has affected every part of the world in 2020, and the purpose of this project reflects in scopes and areas that COVID-19 has impacted (Age, Socio-economic factors related to GDP, locations, Populations, etc.) by analyzing the data of COVID-19 from multiple sets.  

### Research Questions to Answer
  1) Compare the deaths of COVID-19 from a global perspective from the population, population density, and GDP
  
  2) Compare the deaths of COVID-19 from the US perspective from the population, population density, and GDP 
  
  3) Does the age demonstrate the COVID-19 death risk in the United States?
  
  4) Does GDPs for each state have any relationships with Covid-related deaths?
  
  5) How is gender impacted by Covid-19 deaths in the United States?
  
### Data Sets to be Used
http://www.census.gov/data.html

https://covid19api.com/

https://www.bea.gov/

https://coronavirus.jhu.edu/

https://covid.cdc.gov/covid-data-tracker/#cases_casesinlast7days

https://www.cdc.gov/tobacco/data_statistics/mmwrs/byyear/2019/mm6845a2/index.html

https://covidtracking.com/

https://www.census.gov/data/developers.html

### Rough Breakdown of Tasks
  1) Gather the data from sets mentioned above
  2) Clean the data into the project scope
  3) Tasks for individuals:
      - Michael Bien: COVID-19 deaths in the World based on the population, density and GDP 
      - Debra Wu: COVID-19 deaths in the U.S. based on the population, density and GDP
      - Jinah Porter: COVID-19 deaths in the U.S. based on the groups of gender and age 
      - Lupita Lopez: Introduction for the project presentation 

### Written Analysis
  1) Compare the deaths of COVID-19 from a global perspective from the population, population density, and GDP
  
  2) Compare the deaths of COVID-19 from the US perspective from the population 
![DeathsperState](https://user-images.githubusercontent.com/65466578/93837236-f536a500-fc4a-11ea-9642-2e6ff24634cc.png)

In the US, we can see the number of deaths per state and how they rank with each other. We can see that states like New York, California, New Jersey, Florida & Texas rank very high while other states like Hawaii, Wyoming, North Dakota and Alaska rank very low in Covid deaths. 

Naturally, we could assume there is a relationship between population and deaths, with states like Wyoming, North Dakota & Alaska which are much lower in population in comparison to other states. 

![PopulationDeathPercentage](https://user-images.githubusercontent.com/65466578/93837251-01bafd80-fc4b-11ea-8f5a-3375118a1ef6.png)

With this comparison bar chart, we can see that with states like New York and California, both which are very populated rate high on the death rates. However, there are also states like New Jersey, Louisiana, and Massachusetts, that have a higher percentage of death than its population, and states like Texas and Florida that have a high percentage of the population but also rank within the top 5 of deaths.

With the varying numbers, we can use a scatter plot with a linear regression to see what kind of correlation there is between population and deaths.

![DeathsperPopulation](https://user-images.githubusercontent.com/65466578/93837931-96265f80-fc4d-11ea-83f1-c6e1ecd0841d.png)

As we can see here, there is a strong, positive relationship between the death rate and population. This means that as the population grows, so does the death rate related to Covid. This could be due also to overcrowding, lack of resources in hospitals that could also assist in the recovery of infected patients. 
  
  3) Does the age demonstrate the risk level of COVID-19 death in the United States?

![Agebased](https://github.com/debrawu/ProjectOne/blob/master/deaths_by_agegroup.png)

Adding more factors to COVID-19 deaths, we wanted to analyze the relationship between COVID-19 deaths and the age group, since the media has been raising the concern of COVID-19’s vulnerability risk among people who are older. Based on CDC data, approximately 80% of the COVID-19 deaths are from adults age 65 years and older. In contrast, the age group of children age 14 and under has a significantly low death rate (approx. 0.03%) in the last 7 months of this Pandemic period.   
    
  4) Does GDPs for each state have any relationships with COVID-19 deaths?
  
![Screen Shot 2020-09-19 at 11 10 15 AM (2)](https://user-images.githubusercontent.com/65466578/93838053-f5846f80-fc4d-11ea-9d7a-569fba8715c1.png)

  In this portion of the study, we analyze the socio-economic factors that could play into Covid related deaths. The GDP data was gathered by the Bureau of Economic Analysis, and we specifically gathered the data from 2018, when the economy was more stable and unaffected by a pandemic. Our initial hypothesis was that the GDP had an adverse effect on Covid deaths. With a higher GDP, the assumption was that more people would have better access to healthcare and resources in order to recover from the virus.
  
  The heatmap illustrates two layers, the outside layer of GDP and the internal layer of deaths by Covid. Opposite from our initial hypothesis, it seems that with a higher GDP, that there are more deaths related to Covid. 
  
  ![DeathsperRegionalGDP](https://user-images.githubusercontent.com/65466578/93836501-a1c35780-fc48-11ea-9464-1d89dbc141e7.png)
![DeathsperStateGDP](https://user-images.githubusercontent.com/65466578/93836502-a25bee00-fc48-11ea-9c76-0ed097ad4bba.png)

We can see based on the analysis of GDP per state and by region, that actually both represent a positive correlation between the GDP and death, and when there is a growth in GDP, there is also a growth in death. 
  
  5) How is gender impacted by Covid-19 deaths in the US?

![gender](https://github.com/debrawu/ProjectOne/blob/master/deaths_by_sex(line).png)

  
   Our study in COVID-19 deaths in relation to gender indicates that men face a higher risk of death from COVID-19 than women across the age group from newborns to 84 years. This led to two questions, which are:  1) Is there a similar pattern between COVID-19 deaths in gender and other deaths (i.e., cancer, diabetes, heart diseases, etc.) in gender?, and 2) Why? 
    
   In order to answer the first question, we pulled another data from CDC; the number of deaths in top 7 causes in the United States by gender. It’s interesting to find out that the male group contains a higher number of deaths for heart diseases, cancer, unintentional injuries, chronic lower respiratory disease, stroke and diabetes. 
    
![deaths_category](https://github.com/debrawu/ProjectOne/blob/master/Death%20Category%20male%20vs.%20female.png)

   As far as answering “why?” -- we were not able to find the direct correlation between the cause and effect; however, we could make an argument based on the CDC statistics that there is a correlation between the percentage of tobacco product use and deaths rate, since there are 25.8% of men in the United States saying yes to tobacco product use, compared to women in 14.1%. 



  
