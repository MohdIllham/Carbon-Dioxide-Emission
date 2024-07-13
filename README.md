# Carbon Emission Analysis

## Overview
This notebook performs an exploratory data analysis (EDA) to identify which countries have the highest and lowest carbon emissions. The analysis covers the period from 1995 to 2018. The goal is to understand the historical trends in carbon emissions and examine whether countries can improve their positions over time.

**Code:** [`Carbon-Dioxide-Emission`](https://github.com/MohdIllham/Carbon-Dioxide-Emission/blob/main/CO2%20EMISSION.ipynb)

## Table of Contents
- [Overview](#Overview)
- [Installation](#Installation)
- [Data Collection](#Data-Collection)
- [Data Wrangling and Cleaning](#Data-Wrangling-and-Cleaning)
- [Data Visualization](#Data-Visualization)
  + [Stand-out Facts](#Stand-out-Facts)
  + [Top and Bottom Countries by Carbon Emission](#Top-and-Bottom-Countries-by-Carbon-Emission)
  + [Top 5 Countries Over Time](#Top-5-Countries-Over-Timeby-Carbon-Emission)
  + [Variation of Carbon Emission](#Variation-of-Carbon-Emission)
  + [Continent Analysis](#Continent-Analysis)
-[Observations](#Observations)

## Installation
To run the project, you need the following Python libraries:
```
pip install pandas, numpy, warnings, seaborn, matplotlib, plotly, and pycountry_convert
```
## Data Collection
The dataset is loaded from a CSV file containing historical carbon emission data from various countries. The initial data structure and a few sample rows are displayed to understand its content.

## Data Wrangling and Cleaning
- The dataset is inspected for null values, duplicates, and irrelevant columns which are then cleaned or removed.
- The data is grouped by country and year to consolidate emission values.
- The total emissions for each country over the entire period (1995-2018) are calculated.

## Data Visualization

### Stand-out Facts
A series of text-based annotations highlight key facts about carbon emissions:
  - Kazakhstan has the highest carbon emission.
  - Asia has the highest emissions among continents.
  - Australia has the lowest emissions within its continent.
  - Switzerland has the lowest overall emissions.
    
### Top and Bottom Countries by Carbon Emission
A bar plot displays the total carbon emissions from 1995 to 2018 for all countries, sorted to highlight the top and bottom performers.

### Top 5 Countries Over Time
The top 5 countries with the highest emissions are further analyzed:
  - A scatter plot shows the emissions of these countries over the years.
  - A box plot visualizes the variation in emissions for these countries.
    
### Variation of Carbon Emission
The data is divided into five-year intervals, and the variation in carbon emissions is analyzed using a faceted box plot for the top 5 countries.

### Continent Analysis
The data is aggregated by continent, and a bar plot shows the total emissions for each continent from 1995 to 2018

## Observations
 - The total carbon emissions for the top 5 countries show a steady decline from 1995 to 2018.
 - Asia and Europe are the continents with the highest carbon emissions.
 - Notable differences in emission patterns are observed among countries and continents.


