# Microfinance-Project
This repository contains data creation for a microfinance institute and it's solution.

# Getting Started
To start this project work the developer should have fundamental knowledge of python.
Developer has to understand the requirements clearly to implement this task.

# General Description
The project aimed to electrify the households with renewable energy sources. Renewable energy solutions can be a solar LED bulb, solar stove, solar street lighting, solar battery storage. With such a massive amount of data, it is not feasible for a Microfinance Institute to decide which attributes would increase the households' tier ranking.
The Multi-tier Framework (MTF) approach, which aims to track energy access and energy poverty considering all other relevant dimensions, such as capacity, availability, reliability, quality, affordability, legality, health, and safety. 
Multi-Tier Framework (MTF)

| Attribute      | Tier 0  | Tier 1       | Tier 2       | Tier 3   | Tier 4   | Tier 5 |
| :---         | :-------:    | -------:          | :----------- | :------: | ------------: | ------------: |
| Capacity      | Less than 3 W  | At least 3 W       | At least 50 W       | At least 200 W   | At least 800 W   | At least 2 kW |
| Availability       | Less than 4 hours  | At least 4 hours  (Tier 2)    | At least 4 hours  (Tier 2)     | At least 8 hours    | At least 16 hours        | At least 23 hours |
| Reliability      | More than 14 disruptions per week (Tier 2)  | More than 14 disruptions per week   (Tier 2)   |More than 14 disruptions per week (Tier 2)| At most 14 disruptions per week or at most 3 disruptions per week with total duration of more than 2 hours     | > 3 to 14 disruptions per week    | At most 3 disruptions per week with total duration of less than 2 hours|   
|Quality| Household experiences voltage problems that damages appliances (Tier 3)| Household experiences voltage problems that damages appliances (Tier 3)| Household experiences voltage problems that damages appliances (Tier 3)| Household experiences voltage problems that damages appliances (Tier 3)| Voltage problems do not affect use of desired appliances (Tier 5)|  Voltage problems do not affect use of desired appliances (Tier 5)|
|Affordability| Cost of a standard consumption package of 365 kWh per year is more than 5% of household income (Tier 2)|Cost of a standard consumption package of 365 kWh per year is more than 5% of household income (Tier 2)|Cost of a standard consumption package of 365 kWh per year is more than 5% of household income (Tier 2)|Cost of a standard consumption package of 365 kWh per year is less than 5% of household income (Tier 5)|Cost of a standard consumption package of 365 kWh per year is more than 5% of household income (Tier 5)|Cost of a standard consumption package of 365 kWh per year is more than 5% of household income (Tier 5)|
|Legality| No bill payments made for the use of electricity (Tier 3)|No bill payments made for the use of electricity (Tier 3)|No bill payments made for the use of electricity (Tier 3)|No bill payments made for the use of electricity (Tier 3)| Bill is paid to the utility, prepaid card seller, or authorized representative (Tier 5)|Bill is paid to the utility, prepaid card seller, or authorized representative (Tier 5)|
|Health & Safety| Serious or fatal accidents due to electricity connection (Tier 3) |Serious or fatal accidents due to electricity connection (Tier 3)|Serious or fatal accidents due to electricity connection (Tier 3) |Serious or fatal accidents due to electricity connection (Tier 5)| Absence of past accidents (Tier 5)| Absence of past accidents (Tier 5)|

# Part 1 Description
Data Creation:
Dataset has been created for 400 households with random fuctions. Also the 7-attribute are taken into consideration while preparing the survey (dataset). 

Data Cleaning:
Data created by random fuction is not technically sound and hence data cleaning has been performed on the created dataset. With data cleaning I have created a dataset which defines a tier ranking for each households taking to consideration all the attributes.

# Part 2 Description
Data generated has been analysis in this section and 4 highly correlated features are identifies with Pearson Correlation. K Means Clustering has been used to form clusters in order to predict the similarity between the highly correlated features and the other independant variables.

Note- Data analysis, pearson correlation and K Means Clustering is performed on the data from csv file (generated from Part 1) which is attached in the project.

# References
- https://en.wikipedia.org/wiki/Electricity_sector_in_India#cite_note-14
- https://datatofish.com/if-condition-in-pandas-dataframe/
- https://github.com/
- https://stackoverflow.com/
- https://hedera-platform.github.io/report-apide/mtf.html
