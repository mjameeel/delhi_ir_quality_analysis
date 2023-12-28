# AIR QUALITY INDEX ANALYSIS: A CASE STUDY

![Pullution](air_quality.png)
Image by <a href="https://pixabay.com/users/sd-pictures-3553481/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1752876">Ralf Vetterle</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1752876">Pixabay</a>

## INTRODUCTION

In Environmental research, Air quality index (AQI) analysis is a very important task that involves monitoring and analyzing air quality in a certain regions. The goal is to provide a numerical value representative of overall air quality, which is essential for public health and environmental management.

## ABOUT THE DATA

The dataset provided for the project contains air quality measurements for Delhi during January 2023. The dataset includes the following variables:

  * date: Date and time of the measurement.
  * co: Concentration of Carbon Monoxide (CO) in µg/m³.
  * no: Concentration of Nitric Oxide (NO) in µg/m³.
  * no2: Concentration of Nitrogen Dioxide (NO2) in µg/m³.
  * o3: Concentration of Ozone (O3) in µg/m³.
  * so2: Concentration of Sulfur Dioxide (SO2) in µg/m³.
  * pm2_5: Concentration of Particulate Matter (PM2.5) in µg/m³.
  * pm10: Concentration of Particulate Matter (PM10) in µg/m³.
  * nh3: Concentration of Ammonia (NH3) in µg/m³.
The data can be downloaded [here](https://statso.io/air-quality-index-analysis-case-study/).

## PROBLEM STATEMENT

The aim of this analysis is to gain insights into the air quality index in Delhi during January 2023, using the provided dataset. The main task is to:

  * Calculate and analyze the Air Quality Index (AQI) based on pollutant concentrations.
  * Examine the distribution of AQI categories to understand the prevalence of different air quality conditions.
  * Investigate hourly trends in AQI to identify patterns and peak pollution hours.
  * Explore correlations between different pollutants to assess their relationships.
  * Compare the calculated AQI metrics with recommended air quality metrics to evaluate the severity of air quality in Delhi.

## DEPENDENCIES

The following libraries were imported and used for the analysis:

* Pandas
* Matplotlib
* Plotly express

## DATA CLEANING

On inspecting the dataset, there is no missing values, and columns names were intuitive. Except that the date column data type is object. The data type was changed to datetime format.

## EDA

A time series plot was used to explore the concentration levels of exach pollutant over the month period. By leveraging this plot during the EDA process, we gained a comprehensive understanding of concentration levels of the pollutant within the dataset. This insight would serve as a foundation for further analysis and decision-making throughout the project.

## CONCLUSION

The analysis of Air quality index (AQI) is crucial in environmental data science that involves monitoring and analyzing air quality in a specific location. The aim is to provide a numerical value that represent the overall air quality. This is essential for public health and environmental management