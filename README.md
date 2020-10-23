# Suicide Rates Overview from 1985 to 2016
Udacity Data Scientist Nano Degree Capstone Project

## Motivation
This project for the Udacity Data Scientist Nano Degree, It is the Capstone project.
I will be looking at the interactions between suicide rate and certain factor such as HDI and GDP, to 
answer the question: How many people commit suicide per population?

## Data
A dataset that consists on 27820 data points per 12 columns that compares socio-economic info with suicide rates by year and
country

- Country: Includes data of 101 countries
- Year: 1985 to 2016
- Sex: Female or Male
- Age: Group 
  - 5-14 Years
  - 15-24 Years
  - 25-34 Years
  - 35-54 Years
  - 55-74 Years
  - 75+ Years
- SuicidesNo: Number of suicides per country, year, sex and age group.
- Population: 
- Suicides100kPop: Suicide Number every 100k that belongs to certain age group
- CountryYear: Concat of country and Year 
- HDIForYear: Human Development Index for year 
- GDPForYear$: Gross Domestic Product per year 
- GDPPerCapita$: Gross Domestic Product per capita
- Generation:
  - G.I. Generation - born between 1900 - 1920
  - Silent - born between 1921 - 1940
  - Boomers - born between 1941 - 1960
  - Generation X - born between 1961 - 1980
  - Millennials - born between 1981 - 2000
  - Generation Z - born between – 2001- present

## Libraries
- python 3.6.3.
- pandas 0.20.3.
- numpy 1.12.1.
- matplotlib 2.1.0.
- sklearn 0.19.1.
- seaborn 0.9.0

## Files
- Data: suicide-rates.csv
- Project:
  - suicide_rates_overview.ipynb
  - suicide_rates_overview.html

## Blog Post 
The blog post for this project can be found here: https://medium.com/@minguesita/can-we-prevent-suicides-196869b35efc

## License
License: World Bank Dataset Terms of Use

## Acknowledgement
- United Nations Development Program. (2018). Human development index (HDI). Retrieved from http://hdr.undp.org/en/indicators/137506
- World Bank. (2018). World development indicators: GDP (current US$) by country:1985 to 2016. Retrieved from http://databank.worldbank.org/data/source/world-development-indicators#
- [Szamil]. (2017). Suicide in the Twenty-First Century [dataset]. Retrieved from https://www.kaggle.com/szamil/suicide-in-the-twenty-first-century/notebook
- World Health Organization. (2018). Suicide prevention. Retrieved from http://www.who.int/mental_health/suicide-prevention/en/

Projects develop while studying for Udacity Nanodegrees:
- [Data Science Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
- [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002)

## Projects

- [Disaster Response Pipeline](./Disaster_Response_Pipeline/README.md) 
- [Missing Migrants Project](./MissingMigrantsProject/README.md)
- [Suicide Rates Overview](./Suicide-Rates-Overviewt/README.md)
- [Write a Data Science Blog Post](./Write-a-Data-Science-Blog-Post/README.md)
- [Recommendations with IBM](./Recommendations-with-IBM/README.md)


