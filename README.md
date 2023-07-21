# world-bank_data-analysis
Exploratory Data Analysis on Development Indicators and CO2 Emission

The World Bank database is a massive repository socioeconomic, financial, environmental, and health-related data. In this analysis, we have collected the data of the following indicators: 'GNI per capita', 'Life expectancy', 'Compulsory education duration', 'Tertiary enrollment', 'CO2 emission per capita' and 'Total natural resources rent', for more than 150 countries across 40 years. The CO2 emission data is available from 1990 to 2019. Data is collected from the World Bank V2 Indicators API (No authentication is required).
https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-api-documentation

We first conducted a cross-sectional analysis on the relationship between indicators as of the year 2019. CO2 emissions per capita has a strongly positive correlation with GNI per capita. However, the relationship between GNI per capita and CO2 emissions per GNI shows a parabolic shape. CO2 emissions per GNI starts to decrease as GNI per capita increases when the GNI per capita reaches a turning point. has a negative correlation with has CO2 emissions per GNI has a weak negative correlation with GNI per capita but a positive correlation with percentage natural resources rents.

We then analysed the changes in CO2 emission during the past 30 years. CO2 emission per capita was increasing over time while CO2 emission per GNI decreasing. The negative correlation between GNI per capita and CO2 emissions per GNI is persistent across years. Reducing CO2 emssion has a positive impact on next year's economic growth.

Finally we performed a hypothesis test on the difference of average CO2 emission per GNI of natural resource exporters and of other countries. We rejected our null hypothesis and conclude that natural resource-exporting countries have a greater average CO2 emission per GNI.
