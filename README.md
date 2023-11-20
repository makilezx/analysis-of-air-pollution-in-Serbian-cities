# Air Pollution Analysis in Serbian Cities


## Introduction
This repository presents a comprehensive data analysis project focusing on air pollution data from various cities in Serbia. 

## Aim
The main goal of this project is to identify the top three most polluted cities in Serbia by analyzing several air pollutants over a specific time span.

## Data
The dataset used for this analysis is sourced from the European Environment Agency. In fact, the Serbian government agency, SEPA, has a cooperation with EEA for years when it comes to aggregating air quality data. Thus, important data was easily accessible.

## Analysis

- This analysis primarily relies on Python, making extensive use of key libraries such as NumPy and Pandas for effective data manipulation and processing.
  
- Prior to the main analysis, the original dataset underwent refinement. This process involved removing irrelevant cities, pollutants, and years to ensure a focus on the most important data.

- Pollution level values per city for each year span were then calculated, providing crucial insights into the air quality across different cities in Serbia.

- In the final analysis, several pollutants were taken into analysis within the 2019-2021 timeframe, considering 22 cities.

- To address the limitation where not every city has air quality stations measuring every pollutant, and the varying number of stations across cities, a linear mixed model was tested.

- Additional visualizations were created to showcase air pollution levels over the three-year period. An interactive geospatial visualization on the map of Serbia was also made.

- Python libraries Folium and Plotly were used for interactive visualizations, along with Seaborn.

![geospatial](https://github.com/makilezx/analysis-of-air-pollution-in-Serbian-cities/assets/50851469/e08bd2ba-ba99-4158-aa66-101d0bcdbbc6)

