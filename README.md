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

The analysis of Air quality index (AQI) is crucial in environmental data science that involves monitoring and analyzing air quality in a specific location. The aim is to provide a numerical value that represent the overall air quality. This is essential for achieving the United Nations Sustainable Development Goals.

The Air Quality Index (AQI) is closely related to several of the United Nations Sustainable Development Goals (SDGs), particularly those focused on health, clean energy, and sustainable cities. Here's a breakdown of the connections:

**SDG 3: Good Health and Well-being:**

* **Direct impact:** Poor air quality is a major risk factor for respiratory and cardiovascular diseases, leading to millions of premature deaths globally each year. The AQI provides a clear and accessible measure of air pollution levels, allowing individuals and policymakers to take steps to protect health.

**SDG 7: Affordable and Clean Energy:**

* **Source of pollution:** Many sources of air pollution are linked to energy production and use, such as coal-fired power plants, vehicle emissions, and household cooking with polluting fuels. Transitioning to cleaner energy sources like renewables and promoting energy efficiency can significantly improve air quality.

**SDG 11: Sustainable Cities and Communities:**

* **Urban air pollution:** Cities are often hotspots for air pollution due to concentrated traffic, industrial activity, and energy use. The AQI is crucial for monitoring air quality in cities and implementing effective policies to reduce pollution and create healthier urban environments.

**Other relevant SDGs:**

* **SDG 13: Climate Action:** Air pollution is closely linked to climate change, as many of the same pollutants contribute to both issues. Improving air quality can also help mitigate climate change and its associated impacts.
* **SDG 15: Life on Land:** Air pollution can harm ecosystems and biodiversity, affecting plants, animals, and microorganisms. Protecting air quality is essential for maintaining healthy ecosystems.

The AQI plays a vital role in tracking progress towards these SDGs by providing a quantifiable measure of air quality and highlighting the need for action. By monitoring and improving air quality, we can create a healthier and more sustainable future for all.