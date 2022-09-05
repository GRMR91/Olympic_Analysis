# Olympic_Analysis

## Overview
The Olympic games have been a way for athletes from across the globe to compete regardless of social or political differences to celebrate the pinnacle of human capabilities.  This exploratory analysis compares a country's GDP, HDI (Human Development Index) and total population to examine possible relationships between a nation's global standing and its capacity to produce world-class athletes. It aims to define the role a country’s economy plays in an athlete's performance and discover whether the origin of an athlete helps or hinders them on their road to Olympic glory. 

## Data Sources

[Olympic performance data]( https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) - Kaggle (scrapped from sports-reference.com in May 2018) 

[Human Development Report](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI) -  United Nations 

[GDP](https://www.kaggle.com/datasets/tunguz/country-regional-and-world-gdp) - World bank c/o Kaggle 

[World population](https://data.worldbank.org/indicator/SP.POP.TOTL) - World Bank

[Shape file for geographic visualisations](https://datahub.io/core/geo-countries#resource-countries) - Datahub

[GDP Time Series Data](https://data.nasdaq.com/databases/WB/data) - World Bank c/o Nasdaq

## Supporting Documentation
 - [Olympian Database](https://www.olympiandatabase.com/index.php?id=13738&L=1)

 - [Olympic Committee](https://olympics.com/ioc)

## Limitations

This analysis covers the Summer and Winter Olympic Games that took place on alternating years from 1992 to 2016 starting with the Summer Games. It does not cover the Paralympic Games results. The years were selected as they covered a suitable number of games that took place recently and a large amount of reliable data was available in the areas being explored.  

During the cleaning process the following teams were removed because the teams comprised of atheletes of differing nationalities making them unsuitable for this analysis. 
 - Czechoslovakia (only participated in the Games of '92)
 - Unified Team/Soviet Union (only participated in the Games of '92)
 - Individual Olympic Athletes
 - Refugee Olympic athletes

A small number of other countries (less than 5% of total explored) were removed due to a lack reliable economic information.

## Tools and Libraries
Excel
Jupyter Notebooks
Python 
 - Pandas
 - Numpy 
 - Seaborn
 - Matplotlib
 - Sklearn
 - Quandl
 - Folium
 - Json
